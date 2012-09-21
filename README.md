# A Lightweight Ruby wrapper for Stanford Natural Language Processing Group's "Named Entity Recognizer"

http://www-nlp.stanford.edu/software/CRF-NER.shtml

## Install

Use Bundler to install the dependencies:
    bundle install

## Use

To run the default example:
    ruby nlp.rb

This will perform entity recognition on a static, hard-coded sentence.

View <pre><code>nlp.rb</code></pre> to see how the Ruby bindings to Java work using the Ruby-Java Bridge (RJB) and how to pass additional data to the recognizer.
