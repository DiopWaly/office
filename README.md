## Overview

This package will help you integrate ONLYOFFICE Docs into your web application on Node.js.

## Release for the package v1.0.0

### Install the prerequisites on your backend
1. Install **svalley-onlyoffice-controller**:
    ```
    npm install svalley-onlyoffice-controller --save
    ```
2. Add on your backend
    ```
    const onlyfficeController = require('svalley-onlyoffice-controller')
    ```
    **Example :**
    ```
    /**
    * define a handler for uploading files
    */
    router.post('/url-api', onlyfficeController.create);
    ```
### List of method functional
* track: POST method for savaving the document.
* documentCreate: POST method for created a new empty document.
* upload: POST method for uploaded a document from your local.
* createWithModel: POST method for created a new document from a modal.
* saveAsModel: POST method for saved a document like a modal.
* models: GET method for getting all the modals. 
* delFile: DELETE method for deletedg a document. 
