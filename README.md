# Postman
## Спарсить request

POSt raw
```
let post_raw = JSON.parse(request.data);
```
POST form data
```
let post_form_data = request.data
```
GET
```
let get_params = pm.request.url.query.toObject()
```
