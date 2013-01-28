django_polls
============

PROJECT_ROOT = os.path.abspath(os.path.join(os.path.dirname(__file__), os.pardir))
PACKAGE_ROOT = os.path.abspath(os.path.dirname(__file__))

TEMPLATE_DIRS = [
   os.path.join(PROJECT_ROOT, "templates"),
   os.path.join(PACKAGE_ROOT, "polls", "templates"),
]

INSTALLED_APPS = [
    ...
    ...
    'polls',
]

