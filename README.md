# ProductApi
Laravel REST API with Passport Authentication.

Creating token keys for security: ``` php artisan passport:install ```

```
'headers' => [

    'Accept' => 'application/json',

    'Authorization' => 'Bearer '.$accessToken,

] 
```

1) Register API: Verb:POST, URL:http://localhost:8000/api/register

2) Login API: Verb:POST, URL:http://localhost:8000/api/login

3) Product List API: Verb:GET, URL:http://localhost:8000/api/products

4) Product Create API: Verb:POST, URL:http://localhost:8000/api/products

5) Product Show API: Verb:GET, URL:http://localhost:8000/api/products/{id}

6) Product Update API: Verb:PUT, URL:http://localhost:8000/api/products/{id}

7) Product Delete API: Verb:DELETE, URL:http://localhost:8000/api/products/{id}


