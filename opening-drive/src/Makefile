page:
	loopit -data videos.json template.html > ../index.html

watch:
	fswatch -o1 . | while read; do make page; done;
