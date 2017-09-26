# php-word-template-processor

This is a copy of the Template Processor file used in Php Word. 
The main extra features here are the ability to add single and multiple pictures, as well as the ability to add to the header, main body and footer. 

Simply rename the old file and place this file in the same directory. 

### Usage

Replace single search item with single picture.

```
$templateProcessor->setImg("search", [
  "src"=>"image1.jpg",
  "swh"=>"200"
]);
```

Replace single search item with multiple pictures.

```
$templateProcessor->setImages("search", [
  [
    "src"=>"image1.jpg",
    "swh"=>"200"
  ],
  [
    "src"=>"image2.jpg",
    "swh"=>"200"
  ]
]);
```
