
![JBehave Logo](http://jbehave.org/images/jbehave-logo.png)


## Setting up a sample test

* Clone the repo
* Install dependencies `mvn install`
* Update `*.conf.json` files inside the `src/test/resources/conf` directory with your [LambdaTest Username and Access Key]

## Running your tests
* To run a single test, run `mvn test -P single`
* To run parallel tests, run `mvn test -P parallel`

 
## Notes
* You can view your test results on the [Automate dashboard](https://appautomation.lambdatest.com/)
* To test on a different set of browsers, check out our [platform configurator](https://www.lambdatest.com/capabilities-generator/)
* You can export the environment variables for the Username and Access Key of your LT account
  
  ```
  export LT_USERNAME=<LT-username> &&
  export LT_ACCESS_KEY=<LT-access-key>
  ```
  
