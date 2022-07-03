---
layout: post
title: How to set PyMC environment locally
date: 2022-06-09
tags: [gsoc]
description: In the beginning, there was light, well, in my case, great mentors with a great plan. To achieve all the objectives, I had to make sure that I had everything installed correctly and that I understood how making contributions to PyMC works.
---
While this official [tutorial](https://docs.pymc.io/en/stable/contributing/pr_tutorial.html) is very explanatory, 
I will briefly put down the main steps followed by me, which, of course, mostly coincide with the ones from the tutorial.
1. Fork the [main repository](https://github.com/pymc-devs/pymc).
2. Clone it locally either using GitHub Desktop or using the terminal and type 
<br>
<code>git clone git@github.com:'your GitHub handle'/pymc.git</code>
3. Check your working directory by typing <code>pwd</code>
4. Make sure to be the <b>pymc</b> folder. If not use <code>cd pymc</code>
5. Write this <i>(I will explain in the next post the local, origin and upstream branches)</i>
<br>
<code>git remote add upstream git@github.com:pymc-devs/pymc.git</code>
6. Create a virtual environment:
<br>
<code>conda env create -f conda-envs/environment-dev-py39.yml</code>
<br>
<code>conda activate pymc-dev-py39</code>
<br>
<code>pip install -e .</code>
7. Run <b>pre-commit</b> checks:
<br>
<code>pip install pre-commit</code>
<br>
<code>pre-commit run --all</code>
<br>
<code>pre-commit install</code>
8. You can also run tests to make sure everything works:
<br>
<code>pytest -v -k test_math pymc/tests</code>

And that's it 🎉