API test code goes here

everything should be of the format:
1: given this base URL
2: use test-hooks to shove your test data in
3: do the API call(s) you want to test
4: assert the results

means we can prove the API without being reliant on the data
if done nicely, our tests should read out as our API specification...

all these tests should assume the service is running; we'll just put up a script that does "start the docker images then trigger these tests"
