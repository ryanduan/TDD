TDD
===

Test-Driven Django

System: Ubuntu

Python 3.3.2

Django 1.5.2




Note

python manage.py test fts

Creating test database for alias 'default'...
F
======================================================================
FAIL: test_can_create_new_poll_via_admin_site (fts.tests.PollsTest)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "/home/ryan/tdd/TDD/ryantdd/fts/tests.py", line 22, in test_can_create_new_poll_via_admin_site
      self.fail('finish this test')
      AssertionError: finish this test

      ----------------------------------------------------------------------
      Ran 1 test in 8.658s

      FAILED (failures=1)
      Destroying test database for alias 'default'...

