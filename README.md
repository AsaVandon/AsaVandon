"import requests

response = requests.get(""https://www.bing.com/images/search?q=bird"")

if response.status_code == 200:
    html = response.text
    # parse html to find image url
    # download image
    # save image to local file
"
![image](https://user-images.githubusercontent.com/120625202/208047288-f35b3de5-dc46-4272-a5b1-c92a973f56fd.png)
