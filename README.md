# CNN.com Visual Demo

4 Concurrent Sessions   

Runs visual test on CNN.Com Site.

Environment Variables Required:

SAUCE_USERNAME   
SAUCE_ACCESS_KEY   
BUILD_TAG   

Sauce Connect Tunnel environament variable only if needed   
SAUCE_TUNNEL   

Windows 10 Chrome 98.0, and Windows 10 Firefox 2 versions back

Runs Visual test against CNN.com. Run to set baseline by accepting all changes.   
Then run later or the next day to see the changes.

mvn dependency:resolve    
mvn test-compile

Run all tests with: mvn test
