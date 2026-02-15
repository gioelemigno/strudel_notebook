# strudel_notebook
Notebook for music made with Strudel REPL

I do not know how to play any instrument but I want to make some music, Strudel REPL is a very nice tool to start with so here we are.

Problems (i.e. opportunities to learn)
- Strudel REPL does not allow to work on a local file
- To learn how to make music it is necessary to have something like a notebook to take notes on and study

Solution
- Create a docker container
- Use Jupyter Notebook

Inside the container:
```
uv run --with jupyter jupyter notebook
```
