# antd-pro-practice

### defs

yarn create - for creating projects from starter packs

for example yarn create umi name_of_project

### folder structure

mock - for mocking apis 

useful for mocking out ui and "offline mode" development 

public - this is where assets should go 

src
    .umi - runtime generated folder
    components 
    e2e - e2e tests per file
    locales - i18n
    pages - tsx/less components
    utils - global helper functions
    services - api definitions uses umi request 
    swagger - frontend api docs 


test - puppeteer used for e2e tests

