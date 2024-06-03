Repro repo for https://github.com/webdriverio/webdriverio/issues/11999#issuecomment-2145360823

# How this project was created

1. Followed the instructions in https://webdriver.io/docs/gettingstarted

`npm init wdio@latest .`

2. Answered almost everything by default (except for Jasmine and Typescript):

```
? A project named "wdio_jasmine_jest" was detected at "/tmp/wdio_jasmine_jest",
correct? Yes
? What type of testing would you like to do? E2E Testing - of Web or Mobile
Applications
? Where is your automation backend located? On my local machine
? Which environment you would like to automate? Web - web applications in the
browser
? With which browser should we start? Chrome
? Which framework do you want to use? Jasmine (https://jasmine.github.io/)
? Do you want to use a compiler? TypeScript (https://www.typescriptlang.org/)
? Do you want WebdriverIO to autogenerate some test files? Yes
? What should be the location of your spec files?
/tmp/wdio_jasmine_jest/test/specs/**/*.ts
? Do you want to use page objects
(https://martinfowler.com/bliki/PageObject.html)? No
? Which reporter do you want to use? spec
? Do you want to add a plugin to your test setup?
? Would you like to include Visual Testing to your setup? For more information see https://webdriver.io/docs/visual-testing! No
? Do you want to add a service to your test setup?
? Do you want me to run `npm install` Yes
```

3. Edited the auto-generated example and added the example provided in the wdio documentation: https://webdriver.io/docs/custommatchers/

4. Run with `npm run wdio`
