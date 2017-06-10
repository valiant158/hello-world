import requests
from lxml import html
Url = requests.get('url')
Html = html.fromstring(Url.comtent)
Title = Html.xpath('//div/@id')
print Title
