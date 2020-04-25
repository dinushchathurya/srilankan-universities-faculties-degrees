# All Srilankan Universities, Faculties and Undegraduate Degrees

This includes all Srilankan Universities,Faculties & Undergraduate Degree Programmes

### Installation

via composer 

composer require dinushchathurya/srilankan-universities

### Usage 

use Devninja\University\University;


public function exampleFunction(){
    return University::getUniversities(); // Returns all universities
    return University::getFaculties('university'); // Returns faculties of a university
    return University::getDegrees('Faculty'); // Returns degrees of a univeristy
}


