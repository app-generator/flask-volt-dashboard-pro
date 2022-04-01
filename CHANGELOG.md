# Change Log

## [1.0.12] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

## [1.0.11] 2022-02-18 
### Fixes

- Update to `WTForms-3.0.0`

## [1.0.10] 2022-02-17 
### Fixes

- Patch SCSS Compilation for:
  - Nodejs `12.x`, `14.x`
- Update CSS Assets:
  - Compiled with `Node v14.15.0`, `Gulp CLI version: 2.3.0`   

## Unreleased
### Fixes

- 2021-11-10 - `v1.0.10-rc1`
  - ImportError: cannot import name 'TextField' from 'wtforms'
    - Problem caused by `WTForms-3.0.0`
    - Fix: use **WTForms==2.3.3**

## [1.0.9] 2021-09-16
### Improvements & Fixes

- Bump Flask Codebase to [v2.0.0](https://github.com/app-generator/boilerplate-code-flask-dashboard/releases)
  - Dependencies update (all packages)
    - Use Flask==2.0.1 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update 

## [1.0.8] 2021-06-30
### Improvements 

- Update UI - Volt PRO v1.4.1

## [1.0.7] 2021-06-26
### Tooling

- Added scripts to recompile the SCSS files
    - `app/base/static/assets/` - gulpfile.js
    - `app/base/static/assets/` - package.json

## [1.0.6] 2021-06-15

- Correct 404 Links - UI Docs 

## [1.0.5] 2021-05-16
### Dependencies Update

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.6
- Freeze used versions in `requirements.txt`
    - jinja2 = 2.11.3

## [1.0.4] 2021-04-25
### Improvements

- Bump UI: Volt PRO v1.3.1
- UI: [Jinja Volt PRO](https://github.com/app-generator/jinja-template-volt-pro/releases) v1.0.3

## [1.0.3] 2021-03-19
### Improvements

- Codebase: [Flask Dashboard Boilerplate](https://github.com/app-generator/boilerplate-code-flask-dashboard/releases) - v1.0.5
- Freeze used versions in `requirements.txt`
    - flask_sqlalchemy = 2.4.4
    - sqlalchemy = 1.3.23

## [1.0.2] 2021-01-20
### Improvements & Bug Fixes

- UI: [Jinja Volt PRO](https://github.com/app-generator/jinja-template-volt-pro/releases) v1.0.2
- Volt PRO v1.2.0
- Codebase - [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard/releases) v1.0.4

## [1.0.1] 2020-12-29
### Improvements & Bug Fixes

- Update UI - Volt PRO v1.2.0
- Bump Flask codebase - v1.0.2

## [1.0.0] 2020-10-11
### Initial Release
