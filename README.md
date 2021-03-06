# Grain
Welcome to Grain Inventory Manager API. This API can help you to manage your office inventory.

## Preparing
Since this API is built using Python and Django Rest, you need packages that can be installed directly with:
```
$ pip install -r requirements.txt
$ python manage.py migrate
```

## Test
You can do a test by just typing the command:

```
$ python manage.py test
```

## Load Initial Data
For sampling the initial data (rather than entering one by one from the database), you only need to run:
```
$ python manage.py loaddata company.yaml division.yaml user.yaml employee.yaml invenory.yaml
```

## Credits
> Thanks to GDN Engineering Teams. We build with love.

## Licence (MIT)

```
Copyright 2018 Localbin

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software,
and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies
or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS
BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.
```
