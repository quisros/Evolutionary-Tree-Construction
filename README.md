# Evolutionary Tree Construction

An implementation of the fundamental evolutionary tree algorithm **UPGMA** in the GO language. 

### Input format:

* first line - number of species in the distance matrix (let it be n)

* next n lines - the distance matrix with entries in each row separated by tabs

If required, refer to the given sample distance matrices (<code>test-1.txt</code> and <code>test-2.txt</code>) to get more clarity on the input format.

### Running instructions:

* Install Go if not already installed. Refer to [this](https://golang.org/doc/install) page if required. For mac: <code> brew install go</code>

* <code>git clone https://github.com/quisros/evolutionary-tree-construction.git</code>

* <code>cd upgma</code>

* <code>go build</code>

* For simple text-output: <code>./upgma [text-file-name.txt]</code>

* For visualization of the tree: <code>./upgma [text-file-name.txt] > output.txt</code>. Copy the contents of <code>output.txt</code> and paste them into the text panel on the left side of [this](http://viz-js.com) page.

