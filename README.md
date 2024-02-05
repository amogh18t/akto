## Akto.io
Create a traffic processing sdk
# Task 3
Create a traffic processing sdk in any language, **apart from java, js and go.**
    1. You can take reference from https://docs.akto.io/traffic-connections/traffic-data-sources/akto-sdk  and create a simillar SDK.
    2. The primary functionalities of a traffic processing SDK are: 
        1. Log all requests and their responses of the web server
        2. Send the same to a kafka producer
    3. Use good coding practices.
    4. Recommended language options: bash, C++, Ruby or any other language [python is least preferred but allowed]. (Used C++)
    5. You can use any libraries as required.
    6. You may use any simple server for testing pruposes [ e.g. an echo server ]
    7. Bonus: package the SDK, so that it can be used in a plug-and-play manner.
    8. Submit the code repo. Also write steps to use the SDK.

## A simple logging system that captures HTTP request and response information and sends it to a Kafka topic for further processing.

1 Custom Http Servlet Request Wrapper
2 Custom Http Servlet Response Wrapper
3 KafkaProducer
4 LoggingFilter

wrapper design pattern
filter chain -> doFilter