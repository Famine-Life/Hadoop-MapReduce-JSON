Hadoop-MapReduce-JSON
=====================

Given the input author-book tuples, map-reduce program procudes a JSON object which contains all the books from same author in a JSON array

The program uses a combiner to minimize number of key-value pairs generated
from each node.