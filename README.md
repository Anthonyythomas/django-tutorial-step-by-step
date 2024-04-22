# django-tutorial-step-by-step
========================================================

This repository contains the Django project you build in the official
Django tutorial: the `mysite` project with the `polls` app.

Each commit corresponds to a step in the tutorial.

Table of contents:
------------------
Here is a list of all steps in the tutorial.

Part 1:
* [Part 1: Creating a project](https://docs.djangoproject.com/en/5.0/intro/tutorial01/#creating-a-project)
* [Part 1: Creating the Polls app](https://docs.djangoproject.com/en/5.0/intro/tutorial01/#creating-the-polls-app)
* [Part 1: Writing your first view](https://docs.djangoproject.com/en/5.0/intro/tutorial01/#write-your-first-view)

Part 2:
* [Part 2: Database setup](https://docs.djangoproject.com/en/5.0/intro/tutorial02/#database-setup)
* [Step 2: Creating models](https://docs.djangoproject.com/en/5.0/intro/tutorial02/#creating-models)
* [Part 2: Activating models](https://docs.djangoproject.com/en/5.0/intro/tutorial02/#activating-models)
* [Part 2: Playing with the API](https://docs.djangoproject.com/en/5.0/intro/tutorial02/#playing-with-the-api)
* [Part 2: Introducing the Django Admin](https://docs.djangoproject.com/en/5.0/intro/tutorial02/#introducing-the-django-admin)

Part 3:
* [Part 3: Writing more views](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#writing-more-views)
* [Part 3: Write views that actually do something](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#write-views-that-actually-do-something)
* [Part 3: Write views that actually do something - with templates](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#write-views-that-actually-do-something)
* [Part 3: Write views that actually do something - A shortcut: render()](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#a-shortcut-render)
* [Part 3: Raising a 404 error](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#raising-a-404-error)
* [Part 3: Raising a 404 error - A shortcut: get_object_or_404()](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#a-shortcut-get-object-or-404)
* [Part 3: Use the template system](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#use-the-template-system)
* [Part 3: Removing hardcoded URLs in templates](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#removing-hardcoded-urls-in-templates)
* [Part 3: Namespacing URL names](https://docs.djangoproject.com/en/5.0/intro/tutorial03/#namespacing-url-names)

Part 4
* [Part 4: Write a minimal form](https://docs.djangoproject.com/en/5.0/intro/tutorial04/#write-a-minimal-form)
* [Part 4: Write a minimal form - results view](https://docs.djangoproject.com/en/5.0/intro/tutorial04/#write-a-minimal-form)
* [Part 4: Use generic views: Less code is better](https://docs.djangoproject.com/en/5.0/intro/tutorial04/#use-generic-views-less-code-is-better)

Part 5:
* [Part 5: Writing our first test - Create a test to expose the bug](https://docs.djangoproject.com/en/5.0/intro/tutorial05/#create-a-test-to-expose-the-bug)
* [Part 5: Writing our first test - Fixing the bug](https://docs.djangoproject.com/en/5.0/intro/tutorial05/#fixing-the-bug)
* [Part 5: Writing our first test - More comprehensive tests](https://docs.djangoproject.com/en/5.0/intro/tutorial05/#more-comprehensive-tests)
* [Part 5: Test a view - Improving our view](https://docs.djangoproject.com/en/5.0/intro/tutorial05/#improving-our-view)
* [Part 5: Test a view - Testing our new view](https://docs.djangoproject.com/en/5.0/intro/tutorial05/#testing-our-new-view)
* [Part 5: Test a view - Testing the DetailView](https://docs.djangoproject.com/en/5.0/intro/tutorial05/#testing-the-detailview)

Part 6:
* [Part 6: Customize your app’s look and feel](https://docs.djangoproject.com/en/5.0/intro/tutorial06/#customize-your-app-s-look-and-feel)
* [Part 6: Adding a background-image](https://docs.djangoproject.com/en/5.0/intro/tutorial06/#adding-a-background-image)

Part 7:
* [Part 7: Customize the admin form - reordering the fields](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#customize-the-admin-form)
* [Part 7: Customize the admin form - split the form](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#customize-the-admin-form)
* [Part 7: Adding related objects - register Choice with the admin](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#adding-related-objects)
* [Part 7: Adding related objects - remove Choice from admin, add inline](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#adding-related-objects)
* [Part 7: Adding related objects - use TabularInline (instead of StackedInline)](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#adding-related-objects)
* [Part 7: Customize the admin change list - use list_display option](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#customize-the-admin-change-list)
* [Part 7: Customize the admin change list - include was_published_recently()](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#customize-the-admin-change-list)
* [Part 7: Customize the admin change list - add attributes to was_published_recently()](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#customize-the-admin-change-list)
* [Part 7: Customize the admin change list - add list_filter](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#customize-the-admin-change-list)
* [Part 7: Customize the admin change list - add search_fields](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#customize-the-admin-change-list)
* [Part 7: Customize the admin look and feel - Customizing your project’s templates](https://docs.djangoproject.com/en/5.0/intro/tutorial07/#customize-the-admin-look-and-feel)

Part 8:
* [Part 8: Installing Django Debug Toolbar](https://docs.djangoproject.com/en/5.0/intro/tutorial08/#installing-django-debug-toolbar)

## Django Tutorial Step-by-Step
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Clone the Repository](#clone-the-repository)
- [Create a Virtual Environment (optional but recommended)](#create-a-virtual-environment-optional-but-recommended)
- [Activate your Virtual Environment](#activate-your-virtual-environment)
- [Install the Dependencies](#install-the-dependencies)
- [Database Setup](#database-setup)
- [Create a Superuser (optional)](#create-a-superuser-optional)
- [Running the Project](#running-the-project)
- [Testing](#testing)
- [Run all tests](#run-all-tests)
- [Run a single test](#run-a-single-test)

## Prerequisites
- Python 3.6 or later
- Git
- (Optional) Virtualenv or equivalent virtual environment tool

## Installation
#### Clone the Repository

#### With SSH
```bash
git clone git@github.com:Anthonyythomas/django-tutorial-step-by-step.git
cd django-tutorial-step-by-step
```
#### With HTTPS
```bash
git clone https://github.com/Anthonyythomas/django-tutorial-step-by-step.git
cd django-tutorial-step-by-step
```

## Create a Virtual Environment (optional but recommended)
#### If you have virtualenv installed, run:
```bash
virtualenv venv
```
#### If you're using Python 3.3 or later, you can use venv directly:
```bash
python3 -m venv venv
```

# Activate your Virtual Environment
#### On macOS/Linux:
```bash
source venv/bin/activate
```
#### On Windows:
```bash
venv\Scripts\activate
```
## Install the Dependencies
```bash
pip install -r requirements.txt
```

## Database Setup
```bash
python manage.py migrate
```

## Create a Superuser (optional)
```bash
python manage.py createsuperuser
```

## Running the Project
```bash
python manage.py runserver
```
Open the project in a web browser at http://127.0.0.1:8000/.

## Testing
#### Run all tests
```bash
python manage.py test
```
#### Run a single test
```bash
python manage.py test models
```