   provider "aws" {
     region = "Sydney"  
   }

   resource "aws_instance" "Example 1" {
     ami           = "ami-0e326862c8e74c0fe"  
     instance_type = "t2.micro"
   }
