build status: [![Build Status](https://travis-ci.org/greengerong/opencsv-utils.png?branch=master)](https://travis-ci.org/greengerong/opencsv-utils)

===============================
public class Person {

    private int id;

    @Csv("person name")
    private String name;

    @Ignore
    private int age;

    ............
 }

 For person object mapping will be :

 id  => id

 name => person name

 It will ignore age field.
