# Revit API Documentation (Markdown)

This repository contains the Autodesk Revit API documentation converted from the official CHM help file to Markdown format.
It is intended to provide easy, searchable, and web-accessible reference material for Revit API developers, especially those working with Python add-ins.

## Contents

- Markdown files for all Revit API classes, methods, properties, and concepts
- Cleaned and formatted for readability and compatibility with static site generators and documentation tools

## How This Was Made

The documentation was extracted from the official `RevitAPI.chm` file using a custom Python script.
The script:
- Extracts HTML from the CHM file using 7-Zip
- Cleans and converts the HTML to Markdown
- Preserves code samples and API references

## Usage

You can:
- Browse the documentation directly on this GitHub Pages site: [https://yourusername.github.io/revit-api-docs/](https://yourusername.github.io/revit-api-docs/)  
  *(Replace with your actual URL)*
- Clone or download this repository to use the Markdown files locally or integrate with your own tools

## For Cursor Users

You can add this site as a documentation source in Cursor using the "Add Webpage" feature, enabling AI-powered code assistance with direct access to the Revit API docs.

## License

This documentation is derived from Autodesk's official Revit API help files.  
Please refer to Autodesk's terms of use for redistribution or commercial use. 