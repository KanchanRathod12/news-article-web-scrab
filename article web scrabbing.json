pip install newspaper3k


from newpaper import Article

url =" https://time.com"

article = Article(url)
article.download()
article.parse()


txt = article.text
print(txt)

f=open("my_article.txt","w")
f.write(txt)
f.close()
