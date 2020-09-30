# CI / CD

##  ¿Qué es CI y CD?

https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment

## Fases del CI 

* Trigger (Commit)
* Static code Analysis
  * Eslint
  * Prettier
  * TsLint
  * npm audit
  * SonarCloud
* Build Phase
  * Docker
  * Vagrant
* Test phase
  * Execute Tests (API / Integration) 
  * 
  * Si el pipeline va hasta aqui, es continous integration
* Deploy to Dev
* Acceptance testing (UAT / QA)
  * Puede ser manual (continous delivery)
  * Puede ser automatico (continous deployment)
* Deploy to Staging 
* Deploy to Production


## Servicios de CI / CD
* Jenkins (Open Source)
* GitLab CI
* Bitbucket Pipelines
* Github Actions
* Circle CI
* Jenkins
* BitRise (Mobile)
  
## En la capacacitación de hoy

### Local
- Añadir linters
- Añadir Husky
- Añadir Link Staging

### Github
- Pipeline para dev environment
  - Solo se activará cuando la acción sucede en otro lugar que
  - Fases:
    - trigger
    - style check
    - build
    - test