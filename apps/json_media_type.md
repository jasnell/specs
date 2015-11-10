## "json/*"" Primary Media Type

Using "json" as the primary media content type indicates that the content identified conforms to the JSON format as defined by RFC 4627.

Subtypes defined within the "json" tree identify specific profiles or applications of the JSON data format.

The media type "json/plain" is equivalent to the "application/json" media type defined by RFC 4627. Unrecognized sub-types of "json" should be treated as "json/plain".

All content identified using the "json" tree must be valid JSON documents as defined by RFC 4627.

Historically, specific data formats derived from JSON have
used the subtype "+json" suffix defined by RFC 6839. Within
the "json" tree, every "application/yyy+json" media type
variant is equivalent to "json/yyy"

For instance, "json/ld" is equivalent to "application/ld+json".

Every registered subtype in the "json" tree can be used as an RFC 6839 style suffix. For instance, "json/activity+ld".
