# fastify-gcs

## Install

```
npm install --save 1kemalozturk/fastify-gcs
```

## Usage

Import "fastify-gcs" and register it into Fastify instance

```javascript
fastify.register(require('@1kemalozturk/fastify-gcs'), {
  projectId: '',    // [string, required] GCP project id
  keyFilename: ''   // [string, optional] path to service account json file 
})
```
you can access the Cloud Storage client via: 

```javascript
const cloudStorage = fastify.googleCloudStorage
```
