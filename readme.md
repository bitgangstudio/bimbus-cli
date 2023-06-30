Bimbus 📚🚀
===========

Bimbus is a command line tool built with Node.js that leverages OpenAI technology to generate thorough documentation for code files, such as .php, .ts, and more. With Bimbus, you can easily generate comprehensive documentation to enhance the understanding and maintainability of your codebase.

⚠️ Code in Production ⚠️
-------------------

Please note that the code report feature is still in active development and is not yet ready for production usage. While the core functionality of Bimbus is operational, the code report generation is currently being fine-tuned and improved. We appreciate your understanding as we work diligently to provide you with a robust and reliable code documentation tool.

Feel free to explore and utilize the existing functionality of Bimbus, but be aware that the code report feature may not produce optimal results at this stage. We highly value your feedback and suggestions to further enhance the code report capabilities.

Stay tuned for future updates and releases as we continue to refine and expand the code report functionality in Bimbus.

System Requirements
-------------------

To use Bimbus, ensure that you have the following system requirements:

*   Node.js (v14 or higher)
*   npm (v18 or higher)

Installation
------------

To install Bimbus, follow these steps:

1.  Download the Bimbus repository.
2.  Open a terminal or command prompt.
3.  Navigate to the downloaded repository directory.
4.  Run the following bash script to install Bimbus:

    $ ./install.sh
    

Usage
-----

To generate documentation using Bimbus, run the following command:

    $ bimbus -t <OpenAI Access Token> -i <input-file-path> [-o <output-file-directory>]
    

The command accepts the following arguments:

*   `-t` or `--token`: Specifies the OpenAI Access Token.
*   `-i` or `--input`: Specifies the path to the input file containing code to generate documentation for.
*   `-o` or `--output` (optional): Specifies the output directory where the generated documentation will be saved. If not provided, the documentation will be saved in the current working directory.

Examples
--------

Here are a few examples demonstrating the usage of Bimbus:

    $ bimbus -t your-access-token -i /path/to/code.php
    

    $ bimbus -t your-access-token -i /path/to/code.ts -o /path/to/output/directory
    

Additional Resources
--------------------

For more information on how to use Bimbus and customize its behavior, refer to the [Bimbus Documentation](https://link-to-bimbus-documentation).

Contributions and Issues
------------------------

We welcome contributions and feedback! If you encounter any issues or have suggestions for improvements, please submit them in the [Issue Tracker](https://link-to-issue-tracker). Pull requests are also welcome.

License
-------

Bimbus is released under the [MIT License](https://link-to-license).

📝👩‍💻 Happy documenting with Bimbus!