
# SIP TRUNK Interconnection Parameter 
<img width="828" alt="Screen Shot 2022-10-27 at 11 48 55 PM" src="https://user-images.githubusercontent.com/116668420/198351169-4662a972-2edd-4c4a-b610-29b830c96f82.png">
# Getting Started with siskom Voice API

## Introduction

Voice API request
 

## Test the SDK

Unit tests in this SDK can be run using PHPUnit.

1. First install the dependencies using composer including the `require-dev` dependencies.
2. Run `vendor\bin\phpunit --verbose` from commandline to execute tests. If you have installed PHPUnit globally, run tests using `phpunit --verbose` instead.

You can change the PHPUnit test configuration in the `phpunit.xml` file.

## Initialize the API Client

**_Note:_** Documentation for the client can be found [here.](doc/client.md)

The following parameters are configurable for the API Client:

| Parameter | Type | Description |
|  --- | --- | --- |
| `environment` | Environment | The API environment. <br> **Default: `Environment.PRODUCTION`** |
| `timeout` | `int` | Timeout for API calls in seconds.<br>*Default*: `0` |
| `enableRetries` | `bool` | Whether to enable retries and backoff feature.<br>*Default*: `false` |
| `numberOfRetries` | `int` | The number of retries to make.<br>*Default*: `0` |
| `retryInterval` | `float` | The retry time interval between the endpoint calls.<br>*Default*: `1` |
| `backOffFactor` | `float` | Exponential backoff factor to increase interval between retries.<br>*Default*: `2` |
| `maximumRetryWaitTime` | `int` | The maximum wait time in seconds for overall retrying requests.<br>*Default*: `0` |
| `retryOnTimeout` | `bool` | Whether to retry on request timeout.<br>*Default*: `true` |
| `httpStatusCodesToRetry` | `array` | Http status codes to retry against.<br>*Default*: `408, 413, 429, 500, 502, 503, 504, 521, 522, 524` |
| `httpMethodsToRetry` | `array` | Http methods to retry against.<br>*Default*: `'GET', 'PUT'` |
| `username` | `string` |  |
| `password` | `string` |  |

The API client can be initialized as follows:

```php
$client = SiskomVoiceAPILib\SiskomVoiceAPIClientBuilder::init()
    ->username('username')
    ->password('password')
    ->environment('production')
    ->build();
```

## Authorization

This API uses `Basic Authentication`.

## List of APIs

* [Conversation AI](doc/controllers/conversation-ai.md)
* [Call](doc/controllers/call.md)
* [Masking](doc/controllers/masking.md)
* [Translation](doc/controllers/translation.md)
* [Device](doc/controllers/device.md)
* [Agent](doc/controllers/agent.md)
* [Queue](doc/controllers/queue.md)
* [Route](doc/controllers/route.md)
* [IVR](doc/controllers/ivr.md)
* [DID](doc/controllers/did.md)

## Classes Documentation

* [ApiException](doc/api-exception.md)
* [HttpRequest](doc/http-request.md)
* [HttpResponse](doc/http-response.md)

