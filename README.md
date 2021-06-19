# Angular-Folder-Structure
```
.
|-- README.md
|-- angular.json
|-- e2e
|   |-- protractor.conf.js
|   |-- src
|   |   |-- app.e2e-spec.ts
|   |   `-- app.po.ts
|   `-- tsconfig.json
|-- karma.conf.js
|-- package.json
|-- src
|   |-- app
|   |   |-- app-routing.module.ts
|   |   |-- app.component.html
|   |   |-- app.component.scss
|   |   |-- app.component.spec.ts
|   |   |-- app.component.ts
|   |   |-- app.module.ts
|   |   |-- core
|   |   |   |-- constant
|   |   |   |-- core.module.ts
|   |   |   |-- guard
|   |   |   |   |-- auth.guard.spec.ts
|   |   |   |   |-- auth.guard.ts
|   |   |   |   |-- no-auth.guard.spec.ts
|   |   |   |   `-- no-auth.guard.ts
|   |   |   |-- interceptor
|   |   |   |   |-- token.interceptor.spec.ts
|   |   |   |   `-- token.interceptor.ts
|   |   |   |-- pipe
|   |   |   |   |-- date-format.pipe.spec.ts
|   |   |   |   `-- date-format.pipe.ts
|   |   |   |-- services
|   |   |   |   |-- auth.service.spec.ts
|   |   |   |   |-- auth.service.ts
|   |   |   |   |-- http.service.spec.ts
|   |   |   |   |-- http.service.ts
|   |   |   |   |-- logger.service.spec.ts
|   |   |   |   `-- logger.service.ts
|   |   |   `-- utils
|   |   |-- layout
|   |   |   |-- auth-layout
|   |   |   |   |-- auth-layout.component.html
|   |   |   |   |-- auth-layout.component.scss
|   |   |   |   |-- auth-layout.component.spec.ts
|   |   |   |   `-- auth-layout.component.ts
|   |   |   |-- content-layout
|   |   |   |   |-- content-layout.component.html
|   |   |   |   |-- content-layout.component.scss
|   |   |   |   |-- content-layout.component.spec.ts
|   |   |   |   `-- content-layout.component.ts
|   |   |   |-- footer
|   |   |   |   |-- footer.component.html
|   |   |   |   |-- footer.component.scss
|   |   |   |   |-- footer.component.spec.ts
|   |   |   |   `-- footer.component.ts
|   |   |   `-- header
|   |   |       |-- header.component.html
|   |   |       |-- header.component.scss
|   |   |       |-- header.component.spec.ts
|   |   |       `-- header.component.ts
|   |   |-- modules
|   |   |   |-- admin
|   |   |   |   |-- admin-routing.module.ts
|   |   |   |   |-- admin.component.html
|   |   |   |   |-- admin.component.scss
|   |   |   |   |-- admin.component.spec.ts
|   |   |   |   |-- admin.component.ts
|   |   |   |   |-- admin.module.ts
|   |   |   |   |-- category
|   |   |   |   |   |-- category-routing.module.ts
|   |   |   |   |   |-- category.component.html
|   |   |   |   |   |-- category.component.scss
|   |   |   |   |   |-- category.component.spec.ts
|   |   |   |   |   |-- category.component.ts
|   |   |   |   |   `-- category.module.ts
|   |   |   |   |-- dashboard
|   |   |   |   |   |-- dashboard-routing.module.ts
|   |   |   |   |   |-- dashboard.component.html
|   |   |   |   |   |-- dashboard.component.scss
|   |   |   |   |   |-- dashboard.component.spec.ts
|   |   |   |   |   |-- dashboard.component.ts
|   |   |   |   |   `-- dashboard.module.ts
|   |   |   |   |-- inventory
|   |   |   |   |   |-- inventory-routing.module.ts
|   |   |   |   |   |-- inventory.component.html
|   |   |   |   |   |-- inventory.component.scss
|   |   |   |   |   |-- inventory.component.spec.ts
|   |   |   |   |   |-- inventory.component.ts
|   |   |   |   |   `-- inventory.module.ts
|   |   |   |   |-- request
|   |   |   |   |   |-- request-routing.module.ts
|   |   |   |   |   |-- request.component.html
|   |   |   |   |   |-- request.component.scss
|   |   |   |   |   |-- request.component.spec.ts
|   |   |   |   |   |-- request.component.ts
|   |   |   |   |   `-- request.module.ts
|   |   |   |   |-- school
|   |   |   |   |   |-- school-routing.module.ts
|   |   |   |   |   |-- school.component.html
|   |   |   |   |   |-- school.component.scss
|   |   |   |   |   |-- school.component.spec.ts
|   |   |   |   |   |-- school.component.ts
|   |   |   |   |   `-- school.module.ts
|   |   |   |   `-- settings
|   |   |   |       |-- settings-routing.module.ts
|   |   |   |       |-- settings.component.html
|   |   |   |       |-- settings.component.scss
|   |   |   |       |-- settings.component.spec.ts
|   |   |   |       |-- settings.component.ts
|   |   |   |       `-- settings.module.ts
|   |   |   |-- auth
|   |   |   |   |-- auth-routing.module.ts
|   |   |   |   |-- auth.module.ts
|   |   |   |   |-- login
|   |   |   |   |   |-- login-routing.module.ts
|   |   |   |   |   |-- login.component.html
|   |   |   |   |   |-- login.component.scss
|   |   |   |   |   |-- login.component.spec.ts
|   |   |   |   |   |-- login.component.ts
|   |   |   |   |   `-- login.module.ts
|   |   |   |   `-- register
|   |   |   |       |-- register-routing.module.ts
|   |   |   |       |-- register.component.html
|   |   |   |       |-- register.component.scss
|   |   |   |       |-- register.component.spec.ts
|   |   |   |       |-- register.component.ts
|   |   |   |       `-- register.module.ts
|   |   |   `-- student
|   |   |       |-- home
|   |   |       |   |-- home-routing.module.ts
|   |   |       |   |-- home.component.html
|   |   |       |   |-- home.component.scss
|   |   |       |   |-- home.component.spec.ts
|   |   |       |   |-- home.component.ts
|   |   |       |   `-- home.module.ts
|   |   |       |-- inventory
|   |   |       |   |-- inventory-routing.module.ts
|   |   |       |   |-- inventory.component.html
|   |   |       |   |-- inventory.component.scss
|   |   |       |   |-- inventory.component.spec.ts
|   |   |       |   |-- inventory.component.ts
|   |   |       |   `-- inventory.module.ts
|   |   |       |-- student-routing.module.ts
|   |   |       `-- student.module.ts
|   |   `-- shared
|   |       `-- components
|   |           |-- card
|   |           |   |-- card.component.html
|   |           |   |-- card.component.scss
|   |           |   |-- card.component.spec.ts
|   |           |   `-- card.component.ts
|   |           |-- popup-modal
|   |           |   |-- popup-modal.component.html
|   |           |   |-- popup-modal.component.scss
|   |           |   |-- popup-modal.component.spec.ts
|   |           |   `-- popup-modal.component.ts
|   |           |-- side-nav
|   |           |   |-- side-nav.component.html
|   |           |   |-- side-nav.component.scss
|   |           |   |-- side-nav.component.spec.ts
|   |           |   `-- side-nav.component.ts
|   |           |-- slider
|   |           |   |-- slider.component.html
|   |           |   |-- slider.component.scss
|   |           |   |-- slider.component.spec.ts
|   |           |   `-- slider.component.ts
|   |           `-- table
|   |               |-- table.component.html
|   |               |-- table.component.scss
|   |               |-- table.component.spec.ts
|   |               `-- table.component.ts
|   |-- assets
|   |-- environments
|   |   |-- environment.prod.ts
|   |   `-- environment.ts
|   |-- favicon.ico
|   |-- index.html
|   |-- main.ts
|   |-- polyfills.ts
|   |-- styles.scss
|   `-- test.ts
|-- tsconfig.app.json
|-- tsconfig.json
|-- tsconfig.spec.json
`-- tslint.json

```
