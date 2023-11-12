To install Metamorf, you need Python 3.10, and you can install it using pip. 
    
    pip install metamorf

Once installed, you can see all the available commands typing:

    metamorf help

For a quick start, create a directory where you want to locate all the configuration files.

    metamorf init

At this point, you have initialized your environment to configure Metamorf. The default configuration is through
a SQLite database.
  
Metamorf can be deployed where the configuration file says. If SQLite is selected (as default)
and it doesn't exist, Metamorf will create the databases. Try it!

    metamorf deploy

Now you have on your repository all the configuration files and a data and metadata example databases.  
To deploy an example on both databases, just type:

    metamorf deploy-example

A fake dataset is deployed on the data database, and a metadata entry is inserted on the metadata database.
You can just watch all these things with any Database Tool as DBeaver.  
  
If you want to process these metadata, try the command:

    metamorf process

Now all the metadata is processed and the main tables of Metamorf are populated.
To see if all works, you can just type any of the features that Metamorf offers:

If you want to run the processes indicated on the metadata to transform all the fake data, you can just type:

    metadata run

Probably you just want the SQL Files to execute from other platforms, type then:

    metadata output

The results are located on the output folder on your repository.  

The configuration file permits you to configure Metamorf to adapt it to your needs.
For example, one interesting option could be to generate all your datasets on *dbt* format.
To achieve it, just change your *configuration.yml* file, **output** option, **type** value to **dbt**.

      output:
        type: dbt

You can execute again 
    
    metadata output

And now you have all the necessary files for your dbt project.  

This tutorial is just a small demonstration about metamorf and its potential.

*Note: Metamorf works on Windows OS and Linux (tested on Ubuntu)*