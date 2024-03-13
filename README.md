# community-annotations
A place to store and share community-driven manual annotations of Internet resources.

# Annotations
Each CSV file contains annotations for a different type of Internet resources (e.g. AS, IP, Prefix).
The structure is the same for all files:
`resource, annotation_type, annotation_value, contributor, date, url, comment`

- `resource`: identifies the annotated resource. For example, an IP address for the IP.csv file, or an ASN for the AS.csv file. 
- `annotation_type`: is the type/category of the annotation. Usually set to note.
- `annotation_value`: is the annotation for the resource.
- `contributor`: is the name of the person providing the annotation.
- `date`: date when the annotation is made
- `url`: link to a webpage or dataset that could support or explain the annotation.
- `comment`: free text for memos

# Send your annotations
Fork this repository, add your annotations, and create a Pull Request!
