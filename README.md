# Installing protoc
brew install protobuf

# Installing JS protobuf module
npm install google-protobuf

# Compilation
protoc --js_out=import_style=commonjs,binary:. employees.proto 

