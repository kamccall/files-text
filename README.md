# files-text
text file data sources from exercises

# curl use to grab files from python
!curl https://raw.githubusercontent.com/kamccall/files-text/master/gettysburg.txt -o gettysburg.txt
doc1 = open("gettysburg.txt", "r")

# read the document and print its contents
doc1Txt = doc1.read()
print(doc1Txt)
