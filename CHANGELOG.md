# Changelog

## [3.0.5](https://github.com/pydanny/cookiecutter-django/tree/3.0.5) (2020-04-01)

**Closed issues:**

- Django 3.0 support [\#2352](https://github.com/pydanny/cookiecutter-django/issues/2352)

## [3.0.4](https://github.com/pydanny/cookiecutter-django/tree/3.0.4) (2020-03-23)

**Fixed bugs:**

- Potentially invalid file selector pattern for pre-commit [\#2478](https://github.com/pydanny/cookiecutter-django/issues/2478)
- Redis 3.4.0 results in error with flower and celery\_worker [\#2425](https://github.com/pydanny/cookiecutter-django/issues/2425)
- Failing mypy tests in users app with django-stubs [\#2395](https://github.com/pydanny/cookiecutter-django/issues/2395)
- Broken setup with use\_whitenoise=y, use\_compressor=y and cloud\_provider=none [\#2336](https://github.com/pydanny/cookiecutter-django/issues/2336)
- UserDetailView fails on mixed-case usernames [\#1020](https://github.com/pydanny/cookiecutter-django/issues/1020)

**Closed issues:**

- Improve mail service + cloud provider combinations [\#2492](https://github.com/pydanny/cookiecutter-django/issues/2492)
- Celery Flower is not configured for Traefik [\#2394](https://github.com/pydanny/cookiecutter-django/issues/2394)
- Proposal to use python-slim instead of python-alpine [\#2373](https://github.com/pydanny/cookiecutter-django/issues/2373)
- Using WhiteNoise in development when it's enabled? [\#2303](https://github.com/pydanny/cookiecutter-django/issues/2303)
- Upgrade to Traefik v2 [\#2263](https://github.com/pydanny/cookiecutter-django/issues/2263)
- Add pre-commit for generated project [\#2171](https://github.com/pydanny/cookiecutter-django/issues/2171)
- Add an option to choose default email backend \(AWS SES or Mailgun\) [\#2140](https://github.com/pydanny/cookiecutter-django/issues/2140)
- Add isort [\#2123](https://github.com/pydanny/cookiecutter-django/issues/2123)
- Remove coreapi requirement [\#1969](https://github.com/pydanny/cookiecutter-django/issues/1969)
- Migrate to Pathlib [\#1559](https://github.com/pydanny/cookiecutter-django/issues/1559)
- Optionally generate a .gitlab-ci.yml [\#607](https://github.com/pydanny/cookiecutter-django/issues/607)

## [2.2.7](https://github.com/pydanny/cookiecutter-django/tree/2.2.7) (2019-11-04)

**Fixed bugs:**

- Traefik's configuration parameters are not valid in newer version [\#2258](https://github.com/pydanny/cookiecutter-django/issues/2258)

**Closed issues:**

- Look to implement django-q [\#2191](https://github.com/pydanny/cookiecutter-django/issues/2191)

## [2.2.6-01](https://github.com/pydanny/cookiecutter-django/tree/2.2.6-01) (2019-10-06)

**Fixed bugs:**

- No staticfile storage with GCP without Whitenoise [\#2250](https://github.com/pydanny/cookiecutter-django/issues/2250)
- Broken static files with whitenoise=n & cloud\_provider=none [\#2249](https://github.com/pydanny/cookiecutter-django/issues/2249)

**Closed issues:**

- Python 3.7 support [\#2236](https://github.com/pydanny/cookiecutter-django/issues/2236)

## [2.2.6](https://github.com/pydanny/cookiecutter-django/tree/2.2.6) (2019-10-01)

## [2.2.5](https://github.com/pydanny/cookiecutter-django/tree/2.2.5) (2019-09-04)

## [2.2.4](https://github.com/pydanny/cookiecutter-django/tree/2.2.4) (2019-09-04)

**Fixed bugs:**

- 403\_csrf.html should be 403.html, no? [\#2163](https://github.com/pydanny/cookiecutter-django/issues/2163)
- Local Docker: python: can't open file 'manage.py': \[Errno 2\] No such file or directory [\#2074](https://github.com/pydanny/cookiecutter-django/issues/2074)
- Problems with Cookiecutter + Docker + PyCharm [\#1766](https://github.com/pydanny/cookiecutter-django/issues/1766)
- celerybeat-schedule gets nuked on Docker [\#1146](https://github.com/pydanny/cookiecutter-django/issues/1146)

**Closed issues:**

- Celerybeat container fails to start  [\#1793](https://github.com/pydanny/cookiecutter-django/issues/1793)
- Error while Migration. [\#1778](https://github.com/pydanny/cookiecutter-django/issues/1778)
- Postgres not recognizing the user [\#1678](https://github.com/pydanny/cookiecutter-django/issues/1678)
- Installation with compressor fails [\#1677](https://github.com/pydanny/cookiecutter-django/issues/1677)
- Suggestion to Enhance install\_os\_dependencies [\#389](https://github.com/pydanny/cookiecutter-django/issues/389)

## [2.2.1](https://github.com/pydanny/cookiecutter-django/tree/2.2.1) (2019-05-27)

## [2.1.8-01](https://github.com/pydanny/cookiecutter-django/tree/2.1.8-01) (2019-05-27)

**Fixed bugs:**

- Celery task time limit not working [\#2080](https://github.com/pydanny/cookiecutter-django/issues/2080)
- docker-compose -f local.yml up fails on windows [\#2070](https://github.com/pydanny/cookiecutter-django/issues/2070)

**Closed issues:**

- Add PostgreSQL 11 as an option  [\#1989](https://github.com/pydanny/cookiecutter-django/issues/1989)
- Logging improvements [\#928](https://github.com/pydanny/cookiecutter-django/issues/928)
- Changes on celery implementation [\#865](https://github.com/pydanny/cookiecutter-django/issues/865)

## [2.1.8](https://github.com/pydanny/cookiecutter-django/tree/2.1.8) (2019-05-08)

**Closed issues:**

- Docs are out of date [\#2004](https://github.com/pydanny/cookiecutter-django/issues/2004)
- add example how to use mutiple domains in documentation [\#1931](https://github.com/pydanny/cookiecutter-django/issues/1931)

## [2.0.13-02](https://github.com/pydanny/cookiecutter-django/tree/2.0.13-02) (2019-04-16)

**Fixed bugs:**

- Kombu==4.4.0 breaks celery / redis implementation Docker [\#1954](https://github.com/pydanny/cookiecutter-django/issues/1954)
- Windows: Error on docker-compose -f local.yml build [\#1917](https://github.com/pydanny/cookiecutter-django/issues/1917)
- botocore.exceptions.ClientError in Production  when running Collectstatic [\#1885](https://github.com/pydanny/cookiecutter-django/issues/1885)
- Creating a new project with TravisCI support fails first build. [\#1829](https://github.com/pydanny/cookiecutter-django/issues/1829)
- Selected Gulp and CSS compilation. `npm run dev` does not run automatically when docker-compose build+up is invoked [\#1762](https://github.com/pydanny/cookiecutter-django/issues/1762)

**Closed issues:**

- Documentation needs to be updated to add details on Google Cloud Storage [\#2026](https://github.com/pydanny/cookiecutter-django/issues/2026)
- Add utility/requirements-bionic.apt [\#1973](https://github.com/pydanny/cookiecutter-django/issues/1973)
- Dead link in .gitignore comment [\#1972](https://github.com/pydanny/cookiecutter-django/issues/1972)
- kubernetes with simply non-secure [\#1948](https://github.com/pydanny/cookiecutter-django/issues/1948)
- Cookiecutter Django does not support Python 2.... [\#1942](https://github.com/pydanny/cookiecutter-django/issues/1942)
- Replace django-environ library [\#1910](https://github.com/pydanny/cookiecutter-django/issues/1910)
- Migrate to the unified Sentry Python SDK [\#1818](https://github.com/pydanny/cookiecutter-django/issues/1818)
- Postgres authentication error - cannot run local and production on same machine with Docker [\#1785](https://github.com/pydanny/cookiecutter-django/issues/1785)
- Caddy HTTP 500 when uploading a file [\#1740](https://github.com/pydanny/cookiecutter-django/issues/1740)
- Error 500 when trying to log in to heroku project [\#1705](https://github.com/pydanny/cookiecutter-django/issues/1705)
- Redis configuration in local django not needed \(using Docker\) [\#1691](https://github.com/pydanny/cookiecutter-django/issues/1691)
- Default  caddy configuration don't have permissions [\#1666](https://github.com/pydanny/cookiecutter-django/issues/1666)
- In production Caddy is throwing duplicate address error  [\#1622](https://github.com/pydanny/cookiecutter-django/issues/1622)
- Teach Travis to black Cookiecutter Django code [\#1603](https://github.com/pydanny/cookiecutter-django/issues/1603)
- add pylint-common and pylint-django to requirements/local.txt [\#1590](https://github.com/pydanny/cookiecutter-django/issues/1590)
- Add Google Cloud Storage Option in addition to current AWS S3 options [\#1053](https://github.com/pydanny/cookiecutter-django/issues/1053)
- Write test that creates/checks a matrix of all y/n option combinations [\#591](https://github.com/pydanny/cookiecutter-django/issues/591)
- Verify, revise, and improve docs/deployment-with-docker.rst [\#566](https://github.com/pydanny/cookiecutter-django/issues/566)
- Update Heroku deploy docs to include optional integrations \(Celery, Sentry, ...\) [\#449](https://github.com/pydanny/cookiecutter-django/issues/449)

## [2.0.13](https://github.com/pydanny/cookiecutter-django/tree/2.0.13) (2019-02-16)

**Fixed bugs:**

- New version of redis package is the cause of the Error [\#1868](https://github.com/pydanny/cookiecutter-django/issues/1868)
- MediaRootS3BotoStorage causes issue with sorl-thumbnail [\#1771](https://github.com/pydanny/cookiecutter-django/issues/1771)

**Closed issues:**

- SyntaxError leads to exited docker container [\#1856](https://github.com/pydanny/cookiecutter-django/issues/1856)
- Having production only settings leads to deployment bugs [\#1827](https://github.com/pydanny/cookiecutter-django/issues/1827)
- Drop support for bare-bones setups in the project template [\#1800](https://github.com/pydanny/cookiecutter-django/issues/1800)
- Ipython history: keep it around for the django shell [\#1794](https://github.com/pydanny/cookiecutter-django/issues/1794)
- How do you collectstatic in production? [\#1786](https://github.com/pydanny/cookiecutter-django/issues/1786)
- Clarify how to setup Postgres for first time with createdb command [\#1781](https://github.com/pydanny/cookiecutter-django/issues/1781)
- Environment variables error in base.py and local.py [\#1775](https://github.com/pydanny/cookiecutter-django/issues/1775)
- env.example missing [\#1773](https://github.com/pydanny/cookiecutter-django/issues/1773)
- postgresql backup errors [\#1729](https://github.com/pydanny/cookiecutter-django/issues/1729)
- Portainer support when using docker [\#1713](https://github.com/pydanny/cookiecutter-django/issues/1713)
- Adding support postgis [\#1712](https://github.com/pydanny/cookiecutter-django/issues/1712)
- Generate project's setup.py  [\#1708](https://github.com/pydanny/cookiecutter-django/issues/1708)
- Default Postgres Version to 9.6 [\#1686](https://github.com/pydanny/cookiecutter-django/issues/1686)
- Bug report: Setting up a different AWS S3 region in production.py [\#1337](https://github.com/pydanny/cookiecutter-django/issues/1337)
- Verify, revise, and improve docs/developing-locally-docker.rst [\#565](https://github.com/pydanny/cookiecutter-django/issues/565)
- Revise and improve docs/developing-locally.rst [\#564](https://github.com/pydanny/cookiecutter-django/issues/564)

## [2.0.8-01](https://github.com/pydanny/cookiecutter-django/tree/2.0.8-01) (2018-08-30)

## [2.0.8](https://github.com/pydanny/cookiecutter-django/tree/2.0.8) (2018-08-02)

**Closed issues:**

- Upgrade Bootstrap to 4.1 [\#1634](https://github.com/pydanny/cookiecutter-django/issues/1634)

## [2.0.7](https://github.com/pydanny/cookiecutter-django/tree/2.0.7) (2018-07-02)

**Closed issues:**

- Database authentication fails with Docker [\#1672](https://github.com/pydanny/cookiecutter-django/issues/1672)
- Upgrade postgres to 10.4 [\#1669](https://github.com/pydanny/cookiecutter-django/issues/1669)
- Integrate dependencies.io to upgrade Dockerfile base images [\#1336](https://github.com/pydanny/cookiecutter-django/issues/1336)

## [2.0.6](https://github.com/pydanny/cookiecutter-django/tree/2.0.6) (2018-06-01)

**Closed issues:**

- Split issue templates by categories [\#1639](https://github.com/pydanny/cookiecutter-django/issues/1639)
- Unable to restore the database in docker version [\#1623](https://github.com/pydanny/cookiecutter-django/issues/1623)
- Replace awesome-slugify [\#1618](https://github.com/pydanny/cookiecutter-django/issues/1618)
- Remove pycodestyle and pyflakes as implicit dependencies from flakes8 [\#1606](https://github.com/pydanny/cookiecutter-django/issues/1606)
- Install boto3 as extra of django-storages [\#1586](https://github.com/pydanny/cookiecutter-django/issues/1586)
- Uninstall gevent [\#1555](https://github.com/pydanny/cookiecutter-django/issues/1555)
- Integrate npm-check-updates [\#1198](https://github.com/pydanny/cookiecutter-django/issues/1198)
- Integrate npm-check [\#1197](https://github.com/pydanny/cookiecutter-django/issues/1197)
- Add data directory for static files, media files, backup files etc. [\#954](https://github.com/pydanny/cookiecutter-django/issues/954)

## [2.0.5](https://github.com/pydanny/cookiecutter-django/tree/2.0.5) (2018-05-02)

**Fixed bugs:**

- Missing REDIS\_URL [\#1570](https://github.com/pydanny/cookiecutter-django/issues/1570)

## [2.0.4](https://github.com/pydanny/cookiecutter-django/tree/2.0.4) (2018-04-03)

**Fixed bugs:**

- docker/celery exits because celery is run as root [\#1304](https://github.com/pydanny/cookiecutter-django/issues/1304)

**Closed issues:**

- Opbeat sunset [\#1516](https://github.com/pydanny/cookiecutter-django/issues/1516)
- tox.ini out of sync with requirements.txt [\#1494](https://github.com/pydanny/cookiecutter-django/issues/1494)
- CELERY\_BROKER\_URL overriden in entrypoint.sh [\#1235](https://github.com/pydanny/cookiecutter-django/issues/1235)
- Fix the build [\#899](https://github.com/pydanny/cookiecutter-django/issues/899)
- psycopg2 not installed with Windows 10 + Docker [\#841](https://github.com/pydanny/cookiecutter-django/issues/841)
- Start using GitHub's new "Projects" interface for e.g. Django 1.10 upgrade [\#797](https://github.com/pydanny/cookiecutter-django/issues/797)
- Add pytest-cookies [\#586](https://github.com/pydanny/cookiecutter-django/issues/586)
- Logging celery errors with opbeat [\#559](https://github.com/pydanny/cookiecutter-django/issues/559)
- Version check in pre gen hook is not being run [\#534](https://github.com/pydanny/cookiecutter-django/issues/534)
- How do I use the env.sample? [\#490](https://github.com/pydanny/cookiecutter-django/issues/490)

## [2.0.3](https://github.com/pydanny/cookiecutter-django/tree/2.0.3) (2018-03-06)

**Fixed bugs:**

- 500 internal server error on heroku, fresh deploy [\#1527](https://github.com/pydanny/cookiecutter-django/issues/1527)

**Closed issues:**

- What's ACCOUNT\_ALLOW\_REGISTRATION for?  [\#1543](https://github.com/pydanny/cookiecutter-django/issues/1543)
- Opt for .travis.yml [\#1542](https://github.com/pydanny/cookiecutter-django/issues/1542)
- Unconditionally connect to database from DATABASE\_URL env when opting for Docker [\#1541](https://github.com/pydanny/cookiecutter-django/issues/1541)
- Remove requirements\_to\_watch.txt [\#1495](https://github.com/pydanny/cookiecutter-django/issues/1495)
- Drop support for PostgreSQL 9.2 [\#1493](https://github.com/pydanny/cookiecutter-django/issues/1493)
- Refactor gunicorn -w to be set from WEB\_CONCURRENCY env [\#1480](https://github.com/pydanny/cookiecutter-django/issues/1480)
- Use AWS roles instead of AWS\_ACCESS\_KEY\_ID/AWS\_SECRET\_ACCESS\_KEY [\#1453](https://github.com/pydanny/cookiecutter-django/issues/1453)
- Refactor & clean up infrastructure configuration files [\#1315](https://github.com/pydanny/cookiecutter-django/issues/1315)
- Add other database support like MySQL and No-SQL database like MongoDB? [\#1261](https://github.com/pydanny/cookiecutter-django/issues/1261)
- Upgrade docker and docker-compose deployed by Travis [\#1199](https://github.com/pydanny/cookiecutter-django/issues/1199)
- Why use  ./compose/django/entrypoint.sh for postgres-related set ups?  [\#1114](https://github.com/pydanny/cookiecutter-django/issues/1114)
- Fix newlines madness [\#667](https://github.com/pydanny/cookiecutter-django/issues/667)
- Move to the python:alpine docker image [\#498](https://github.com/pydanny/cookiecutter-django/issues/498)

## [2.0.2](https://github.com/pydanny/cookiecutter-django/tree/2.0.2) (2018-02-20)

## [1.11.10](https://github.com/pydanny/cookiecutter-django/tree/1.11.10) (2018-02-01)

## [1.11.9](https://github.com/pydanny/cookiecutter-django/tree/1.11.9) (2018-01-15)

**Fixed bugs:**

- Generated project's .gitignore file contains unresolved cookiecutter template tags [\#1035](https://github.com/pydanny/cookiecutter-django/issues/1035)

**Closed issues:**

- Re-organize compose/ into environment-specific file groups [\#1316](https://github.com/pydanny/cookiecutter-django/issues/1316)
- Use Unix, not Windows environment variable format in Caddyfile [\#1310](https://github.com/pydanny/cookiecutter-django/issues/1310)
- Remove pycharm service from Docker setup [\#1302](https://github.com/pydanny/cookiecutter-django/issues/1302)
- Adopt the same celery\* service extension model for production.yml as for local.yml [\#1297](https://github.com/pydanny/cookiecutter-django/issues/1297)
- Stop providing POSTGRES\_\* envs to django service? [\#1296](https://github.com/pydanny/cookiecutter-django/issues/1296)
- Document custom\_bootstrap\_compilation project generation option [\#1266](https://github.com/pydanny/cookiecutter-django/issues/1266)
- custom\_bootstrap\_compilation not documented [\#1265](https://github.com/pydanny/cookiecutter-django/issues/1265)
- Fix docs erros/typos [\#1263](https://github.com/pydanny/cookiecutter-django/issues/1263)
- Rename Dockerfile-dev to local.Dockerfile [\#1256](https://github.com/pydanny/cookiecutter-django/issues/1256)
- {% if cookiecutter.use\_celery == 'y' %} compose section produces duplicate images [\#1255](https://github.com/pydanny/cookiecutter-django/issues/1255)
- Support RabbitMQ [\#1234](https://github.com/pydanny/cookiecutter-django/issues/1234)
- Rename dev.yml to local.yml [\#1226](https://github.com/pydanny/cookiecutter-django/issues/1226)
- Introduce development-time Celery services [\#1225](https://github.com/pydanny/cookiecutter-django/issues/1225)
- docker-compose up static files cannot be found by wsgi nor nginx [\#1204](https://github.com/pydanny/cookiecutter-django/issues/1204)
- Add PyPi badge indicating the latest stable release available [\#1202](https://github.com/pydanny/cookiecutter-django/issues/1202)
- Pin mailhog Docker image [\#1200](https://github.com/pydanny/cookiecutter-django/issues/1200)
- Unable to use Login System in Production [\#1195](https://github.com/pydanny/cookiecutter-django/issues/1195)
- Nginx gets stuck in redirect loop on production [\#1173](https://github.com/pydanny/cookiecutter-django/issues/1173)
- Add a pre-hook that checks the python version [\#1141](https://github.com/pydanny/cookiecutter-django/issues/1141)
- Document that Cookiecutter Django is secure by default [\#622](https://github.com/pydanny/cookiecutter-django/issues/622)
- Update README with gulp option [\#604](https://github.com/pydanny/cookiecutter-django/issues/604)
- Lets Encrypt [\#471](https://github.com/pydanny/cookiecutter-django/issues/471)
- Better testing for this cookiecutter [\#186](https://github.com/pydanny/cookiecutter-django/issues/186)

## [1.10.7](https://github.com/pydanny/cookiecutter-django/tree/1.10.7) (2017-04-21)

**Closed issues:**

- \[question\] Should we replace links with depends\_on in docker-compose configs? [\#1091](https://github.com/pydanny/cookiecutter-django/issues/1091)
- Fix indentation in nginx.conf [\#807](https://github.com/pydanny/cookiecutter-django/issues/807)
- Error using docker with dev.yml [\#414](https://github.com/pydanny/cookiecutter-django/issues/414)
- Add support for reading settings from `.env` file. [\#197](https://github.com/pydanny/cookiecutter-django/issues/197)

## [1.9.9-05](https://github.com/pydanny/cookiecutter-django/tree/1.9.9-05) (2016-09-29)

## [1.9.9-04](https://github.com/pydanny/cookiecutter-django/tree/1.9.9-04) (2016-09-21)

**Closed issues:**

- Please make a new tag for "Project Organization" or somesuch for discussion tickets [\#800](https://github.com/pydanny/cookiecutter-django/issues/800)
- Update docker docs [\#706](https://github.com/pydanny/cookiecutter-django/issues/706)

## [1.9.9-03](https://github.com/pydanny/cookiecutter-django/tree/1.9.9-03) (2016-08-26)

## [1.9.9-02](https://github.com/pydanny/cookiecutter-django/tree/1.9.9-02) (2016-08-26)

**Closed issues:**

- Change use\_python2 \[N\] to use\_python3 \[Y\] [\#747](https://github.com/pydanny/cookiecutter-django/issues/747)

## [1.9.9](https://github.com/pydanny/cookiecutter-django/tree/1.9.9) (2016-08-16)

**Closed issues:**

- Remove warning from docs/index.rst [\#603](https://github.com/pydanny/cookiecutter-django/issues/603)
- Wait for postgres container to start [\#602](https://github.com/pydanny/cookiecutter-django/issues/602)
- Use the minified Bootstrap CSS and JS [\#589](https://github.com/pydanny/cookiecutter-django/issues/589)
- Link to the documentation from the README [\#588](https://github.com/pydanny/cookiecutter-django/issues/588)
- Gulp support [\#580](https://github.com/pydanny/cookiecutter-django/issues/580)
- Add Apache 2 as a license option [\#572](https://github.com/pydanny/cookiecutter-django/issues/572)
- Move warnings in README to a Troubleshooting section or document [\#563](https://github.com/pydanny/cookiecutter-django/issues/563)
- Remove django-secure [\#562](https://github.com/pydanny/cookiecutter-django/issues/562)
- git pre/post commit hooks [\#556](https://github.com/pydanny/cookiecutter-django/issues/556)
- Make Grunt optional? [\#476](https://github.com/pydanny/cookiecutter-django/issues/476)

## [1.9.6b](https://github.com/pydanny/cookiecutter-django/tree/1.9.6b) (2016-05-24)

**Closed issues:**

- Remove raven.contrib.django.raven\_compat.middleware.Sentry404CatchMiddleware? [\#367](https://github.com/pydanny/cookiecutter-django/issues/367)

## [1.9.6](https://github.com/pydanny/cookiecutter-django/tree/1.9.6) (2016-05-04)

## [1.9.3](https://github.com/pydanny/cookiecutter-django/tree/1.9.3) (2016-03-02)

**Closed issues:**

- Add py.test as testing runner/framework [\#196](https://github.com/pydanny/cookiecutter-django/issues/196)

## [1.8.7](https://github.com/pydanny/cookiecutter-django/tree/1.8.7) (2015-12-13)

## [1.8.6](https://github.com/pydanny/cookiecutter-django/tree/1.8.6) (2015-11-24)

## [1.8.5](https://github.com/pydanny/cookiecutter-django/tree/1.8.5) (2015-10-30)

**Closed issues:**

- Replace memcached with redis as cache [\#221](https://github.com/pydanny/cookiecutter-django/issues/221)
- Lack of app.json [\#218](https://github.com/pydanny/cookiecutter-django/issues/218)
- Add support for whitenoise [\#213](https://github.com/pydanny/cookiecutter-django/issues/213)
- And and encourage use of 'CHANGELOG.md' [\#198](https://github.com/pydanny/cookiecutter-django/issues/198)
- Implement a proper secret key [\#3](https://github.com/pydanny/cookiecutter-django/issues/3)

## [1.7.7](https://github.com/pydanny/cookiecutter-django/tree/1.7.7) (2015-04-26)

**Closed issues:**

- support for django-storages / django AWS S3 media store on python3 [\#161](https://github.com/pydanny/cookiecutter-django/issues/161)
- Python 3.4 and python-memcached [\#135](https://github.com/pydanny/cookiecutter-django/issues/135)

## [1.6.6](https://github.com/pydanny/cookiecutter-django/tree/1.6.6) (2014-09-03)

## [0.1.0](https://github.com/pydanny/cookiecutter-django/tree/0.1.0) (2013-09-15)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
