# A Lightweight Ruby wrapper for Stanford Natural Language Processing Group's "Named Entity Recognizer"

http://www-nlp.stanford.edu/software/CRF-NER.shtml

## Install

Use Bundler to install the dependencies:
<pre><code> bundle install </code></pre>

## Use

To run the default example:
<pre><code> ruby nlp.rb </code></pre>

This will perform entity recognition on a static, hard-coded sentence.

View *nlp.rb* to see how the Ruby bindings to Java work using the Ruby-Java Bridge (RJB) and how to pass additional data to the recognizer.
