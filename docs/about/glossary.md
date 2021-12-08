# Glossary
_I read the word(s) X on this site, or heard them in relation to TaxonWorks.  What do they mean according to this community?_

### Pull Request
A means to suggest changes to a website or code repository by editing a clone of that respository and then sending a message back to the origin that includes those changes. The changes can be considered by the maintainers of the original respostory and integrated, or not.


### Buffered
A prefix (`buffered_`) used to indicate verbatim text that is part of a CollectionObject record. Buffered fields are used TaxonWorks in a digitization workflow as the first step of transcribing labels, or images, to digital data. Buffered fields are write-once, they after addition they should not be changed, nor do they track changes to `parsed` values.

### Cached (values)
Fields prefixed in `cached_` are auto-generated by TaxonWorks based on other values in the record and/or records related to the record.  They are used as indicies for searching and for display purposes, particularly `cached_<>_html` values.

### Context sensitive
Something that appears similar at the outset (e.g. an Icon), but changes in behaviour or appearance given where and when it is encountered in the application.

### Hot keys
Typing a combination of keys to trigger a behaviour in the [UI](/about/glossary#UI). Unversaly hot keys include concepts like `ctrl-c` for "Copy text to clipboard".  TaxonWorks has numerous hot key combinations that speed tasks.

### Identifiers
Identifiers identify instances, i.e. specific things. TaxonWorks supports many different types of identifiers, and multiple identifiers can be added to individual instances.  Some identifier types map 1:1 with physical things like the catalog number attached to specimen in collections, others types are strictly digitial.  Some identifiers are `Global`, some are `Local`. Global identifiers are those that come from well thought out systems that mint identifiers that are intended to be truly globally (universally) unique.  Local identifiers have a user-defined Namespace (the fixed bit of the identifier that doesn't change across the identifier) and a value, which must be unique within that Namespace.

### Naïve matching
Used in context of tracing text in `buffered` fields to the `verbatim` fields include parsed out values.  "Naïve" means we anticipate a very simple match, string to string, no fuzziness, no AI, etc.

### Parsing
Breaking down `buffered` or `verbatim` values into further fields, or semantic relationships.

### Parsed values
In TaxonWorks `parsed values` are the formalized representation of the data.  For example the verbatim date "12.iv.1997" parsed into three fields in TaxonWorks: `start_date_day` (12), `start_date_month` (4), `start_date_year (1997).

### Project
An instance of TaxonWorks supports multiple project.  Each project may have one or more users.  Data in one project, with a couple of key exceptions ("Community" data) are only accessible in that project.

### Staged (or staged images)
A reference to a digitization process in where all data are layed out for complete capture within an image.  TaxonWorks uses stages that have areas defined to match specific types of data, for example "Catalog numbers", "Specimen", "Image registration".

### Stage 2
A temporary(?) code-name referencing a step in the digitization process that represents moving from Buffered or Verbatim values to `parsed values`.

### UI
User interface. The buttons, inputs, layout, and views in the application.

### UX
User experience.  How you navigate, interpret, think about and make use of the [UI](/about/glossary#UI).

### Verbatim fields
Verbatim fields in TaxonWorks are a small set of CollectingEvent fields that contain parts of the Verbatim or Buffered values.  For example given a label like:
```
USA:TX:Brazos Co.
Lick Creek Park
12.iv.1997
M. Yoder, YPT
```
Then the TaxonWorks verbatim fields `verbatim_locality` would contain 'Lick Creek Park' and the `verbatim_date` would include `12.iv.1997`.


## Other glossaries and descriptions

_Heard a term in the context of a biodiversity informatics discussion that you don not understand? One of these resources might define it._

* [TDWG Standards](https://www.tdwg.org/standards/) - TaxonWorks exports, and maps to numerous TDWG defined terms.
