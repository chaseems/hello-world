# hello-world
My first repository on GitHub.


Azure Maps Service
URL = 'https://atlas.microsoft.com/search/address/batch/sync/json?api-version=1.0&subscription-key={sub_key}'.format(sub_key=sub_key)
print('URL:{}'.format(URL))
r03 = requests.post(url=URL,json=data03)
print(r03.json())
