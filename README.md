<p align="center">
    <img src="https://img.shields.io/badge/version-1.0.0-blue">
    <img src="https://img.shields.io/badge/build-passing-yellowgreen">
    <img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/dinushchathurya/srilankan-universities-faculties-degress/total?style=plastic">
    <img src="https://img.shields.io/badge/dependencies-up%20to%20date-orange">
    <img src="https://img.shields.io/badge/coverage-90%25-yellowgreen">
    <img src="https://img.shields.io/badge/rating-★★★★☆-brightgreen">
    <img src="https://img.shields.io/badge/uptime-100%25-brightgreen">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/dinushchathurya/srilankan-universities-faculties-degress?style=plastic">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/dinushchathurya/srilankan-universities-faculties-degress?style=plastic">
    <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/dinushchathurya/srilankan-universities-faculties-degrees?style=plastic">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/dinushchathurya/srilankan-universities-faculties-degress?style=plastic">
   <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/dinushchathurya/srilankan-universities-faculties-degress">
    <a href="https://dinushchathurya.github.io/">
    <img alt="Website" src="https://img.shields.io/website?down_message=red&style=plastic&up_message=online&url=https%3A%2F%2Fdinushchathurya.github.io%2F">
    </a>
    <img alt="Twitter URL" src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2FDinushChathurya">
    <img src="https://img.shields.io/badge/made%20with%20love-by%20srilanka-orange">
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

