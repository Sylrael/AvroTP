# AvroTP

## Serializing and deserializing with code generation
Defining a schema : `user.avsc`
Code generation : create class `User` based on the `scheme`

`User`  
`DatumWriter<User>`  
`DataFileWriter<User>`  
`DatumReader<User>`  
`DataFileReader<User>`  

## Serializing and deserializing without code generation
Without code generation : use of `scheme` and `GenrericRecord`  

`Schema`  
`GenericRecord<GenericRecord>`  
`DataFileWriter<GenericRecord>`  
`DatumReader<GenericRecord>`  
`DataFileReader<GenericRecord>`  