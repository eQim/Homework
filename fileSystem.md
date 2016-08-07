mkdir homeWork2
cd homeWork2
touch index.html
mkdir content
cp index.html content
mkdir newContent
cd content
mv index.html ../newContent/index.html
rmdir content
cd newContent
mv index.html newIndex.html
chmod 740 newIndex.html
