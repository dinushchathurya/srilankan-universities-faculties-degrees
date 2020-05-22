<p align="center">
    <img src="https://img.shields.io/badge/version-1.0.0-blue">
    <img src="https://img.shields.io/badge/build-passing-yellowgreen">
   <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/dinushchathurya/srilankan-universities-faculties-degress">
    
    
</p>

# All Srilankan Universities, Faculties and Undegraduate Degrees

This includes all Srilankan Universities,Faculties & Undergraduate Degree Programmes

### Installation

via composer

`composer require dinushchathurya/srilankan-universities`

### Usage 

```sh 
use Devninja\University\University;

public function exampleFunction(){

    return University::getUniversities(); // Returns all universities 
    return University::getFaculties('University'); // Returns faculties of university 
    return University::getDegrees('Faculty'); // Returns degrees of a univeristy 
}
```

# Contributing

 Author [Dinush Chathurya](https://dinushchathurya.github.io/)

