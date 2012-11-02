# httpclient-shaded

Shaded namespace from `org.apache.http` to `org.apache.shaded.http` and including httpclient-cache.

You can use this jar in android projects alongside the old httpclient version packaged in android.

## Package content

* [httpcore (4.2.2)](http://mvnrepository.com/artifact/org.apache.httpcomponents/httpcore/4.2.2)
* [httpclient (4.2.2)](http://mvnrepository.com/artifact/org.apache.httpcomponents/httpclient/4.2.2)
* [httpmime (4.2.2)](http://mvnrepository.com/artifact/org.apache.httpcomponents/httpmime/4.2.2)
* [httpclient-cache (4.2.2)](http://mvnrepository.com/artifact/org.apache.httpcomponents/httpclient-cache/4.2.2)
* [fluent-hc (4.2.2)](http://mvnrepository.com/artifact/org.apache.httpcomponents/fluent-hc/4.2.1)

## Usage

Download the [httpclient-shaded-4.2.2.jar](http://github.com/larskuhnt/httpclient-shaded/downloads/httpclient-shaded-4.2.2.jar) and include it in your project.

Import the classes with the namespace `org.apache.shaded.http` instead of `org.apache.http`.

## Example

    import org.apache.shaded.http.client.HttpClient;
    import org.apache.shaded.http.client.methods.HttpGet;

## License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
