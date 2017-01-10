# django-unleashed

A workspace for learning the basics of the Django framework.  This is primarily based on Andrew Pinkham's book [*Django Unleashed*](https://django-unleashed.com/), whose repo is [here](https://github.com/jambonrose/DjangoUnleashed-1.8/).

## Getting Started

A handful of resources provide a good point of comparison:

* "[Starting a Django Project](https://realpython.com/learn/start-django/)", a post on [*Real Python*](https://realpython.com/);
* The slides to a talk "[Python, Django + Data Analytics](http://cs.lewisu.edu/~klumpra/camssem2015/django.pdf)", by Curt Lebensorger, since this specifically brings [Anaconda](https://www.continuum.io/) into the mix.

You might also want the [Conda cheat sheet](http://conda.pydata.org/docs/_downloads/conda-cheatsheet.pdf) handy.

The basic setup is as follows:

```bash
> conda create --name djangotude django
> source activate djangotude
> conda list
> conda update --all # get latest versions of packages
> mkdir django-unleashed/
> cd django-unleashed
> django-admin startproject suorganizer
> source deactivate # to close virtual environment
```

This gives us the following project directory.

```
django-unleashed/
+-- suorganizer/
	+-- manage.py
	+-- suorganizer/
		+-- __init__.py
		+-- settings.py
		+-- urls.py
		+-- wsgi.py
```

Now we're off to the races.