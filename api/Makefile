TESTS=test/*.js
test:
	ELASTICSEARCH_NOW=2014-04-05 ELASTICSEARCH_INDEX=fbopen_api_test ELASTICSEARCH_HOST=localhost mocha --timeout 15000 --reporter nyan $(TESTS)

.PHONY: test
