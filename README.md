# automationpractice
Cucumber framework with Cucumber JVM Parallel Run

This Framework specifically designed to run UI Automation using Maven
  Run in Multiple browser parallel for the given browser
  It also handles Tag in maven command line
  
  Example:
  mvn test -Dbrowser=chrome  -- Browsertype can either be chrome or firefox ; but at a time only one browsertype
  This command triggers multiple instance of browser and each browser instance uses a feature file to run the scenarios.
  
  Same way we can add other command line parameters to run specific tags
  mvn test -Dbrowser=firefox -Dcucumber.options="--tags @sanity,@functional"
  
  
