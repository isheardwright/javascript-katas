## What you will Learn?

This Lab-3 teaches you how to create public, private, and static propertis and functions.

## Instructions:

Create the new tool using lab1
 	  
Create public, private and static variable as given below,  

    $.widget("gensler.lab3tool", {
        // public class variables go here
        version: "0.1.0", // http://semver.org
        // public instance variables are in options
        options: {
            title: 'Title',
            instance: {
                name: 'lab3tool',
            },
            //private instance variable go here
            _create: function() {
                this.instanceVar = "huzzah!"
                return this.instanceVar;
            },

        },
        });

By using Lab2 print the public, private and static properties in the console.

