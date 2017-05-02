# ee-rate limit

[![Greenkeeper badge](https://badges.greenkeeper.io/eventEmitter/ee-rate-limiter.svg)](https://greenkeeper.io/)


## installation
	
	npm install ee-rate-limiter

## usage

	// limit to 100 items / minute
	var rate = new RateLimiter( { rate: 100, range: 60 } );


	if ( rate.ok() ){
		// ok

	}
	else {
		// rate limit exceeded

	}