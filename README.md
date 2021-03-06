# rdf-mongo :: MongoDB storage adapter for RDF.rb

This is an RDF.rb storage adapter for MongoDB.

See <http://blog.datagraph.org/2010/04/rdf-repository-howto> for an overview.

## Versioning and backwards compatibility

Moving forward, the versioning will reflect the RDF.rb version number for which all rdf-specs are passing.

It should also be noted that prior to 1.0, there are no guarantees of backwards compatibility for data stored using previous versions of the gem.  This is to make optimizing the schema for MongoDB easy.

## Requirements

You'll need the 'mongo', 'rdf', 'rdf-spec', and 'rspec' libraries.  The easiest way to install these is via RubyGems.

    $ sudo gem install mongo rdf rdf-spec rspec rdf-mongo
    

### Support

Please post questions or feedback to the [W3C-ruby-rdf mailing list][].

### Authors
 * [Pius Uzamere][] | <pius@alum.mit.edu> | <http://github.com/pius> | <http://pius.me>

### Thank you

* Ben Lavender (author of the adapter skeleton) | <blavender@gmail.com> | <http://github.com/bhuga> | <http://bhuga.net> | <http://blog.datagraph.org>

### License

MIT License

[W3C-ruby-rdf mailing list]:        http://lists.w3.org/Archives/Public/public-rdf-ruby/
[Pius Uzamere]: http://pius.me
