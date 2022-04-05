# NLP-colab

## How to run this project on your machine.
### I would recommend using google colab for this, which is the easiest to run without errors and can be temporarily deployed using ngrok library.

Because of outdated versions or unsupported libraries, you may get errors. For example, pytorch was not supported by python 3.9, only recently added to the list of supported in April 2022.
You might have problems installing the grammar checker libraries because the project was started 2-3 years ago with outdated libraries. If errors occur, you need to do some research.
But the best way to ignore them, use google colab or some remote python compiler that should support all versions of the libraries.
The website was created using the flask framework for python.

### How to run and deploy this project in google colab
   1. Here runs the <a href="https://colab.research.google.com/drive/1RBMLPklRl4KG0iAsXW0dK3CAmWvkhPRd">.ipynb</a> code which starts with loading the libraries, you can do the same on your machine.
   2. Find the location of the files in colab and place them with the files on top. `there will be .ipynb file, do not include it`
   3. Then run all the commands in the <a href="https://colab.research.google.com/drive/1RBMLPklRl4KG0iAsXW0dK3CAmWvkhPRd">.ipynb</a> file, one by one.
   4. Finally, you will have 2 routes: `grammar check` and `summarization`.

`Ngrok` is used to check your work in production mode, you can share the link with your friends.
But first of all you have to understand its basic concept.
Useful Links:

 * <a href="https://www.youtube.com/watch?v=7u0KBWlA-Dc&list=LL&index=2&t=1s">Run Your Flask App In Google Colab | Ngrok</a>
 * <a href="https://www.youtube.com/watch?v=649BcMeJI8c&list=LL&index=1">Run Flask Apps Directly From Google Colab</a>
