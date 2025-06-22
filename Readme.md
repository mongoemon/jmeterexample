# JMeter Test Plan Files Overview

This directory contains JMeter test plans for a variety of API and web testing scenarios. Each file demonstrates a different aspect of testing, using real public endpoints.

## Objectives
- Provide ready-to-use examples for functional, negative, data-driven, and content-specific API/web testing.
- Cover a wide range of test types: JSON, XML, HTML, plain text, positive/negative, and data-driven.
- Serve as templates for your own API or web testing projects.

## File Descriptions
- **basic_api_test.jmx**: Tests a single JSON API endpoint for status code and key fields.
- **json_array_response.jmx**: Tests a JSON array response, asserting array structure and key fields.
- **xml_response.jmx**: Tests an XML response, asserting presence of XML tags.
- **html_response.jmx**: Tests an HTML response, asserting presence of specific HTML tags.
- **plain_text_response.jmx**: Tests a plain text response, asserting presence of key lines.
- **01_basic_functional_test.jmx**: Demonstrates basic functional API testing (GET, assertions for response and status code).
- **02_positive_negative_test.jmx**: Demonstrates positive and negative testing (valid and invalid requests, status code assertions).
- **03_data_driven_test.jmx**: Demonstrates data-driven testing using a CSV file (`data.csv`) for parameterized requests.
- **data.csv**: Sample data file for data-driven testing (used by 03_data_driven_test.jmx).

## How to Run the Test Plans
1. Open Apache JMeter.
2. Use `File > Open` to load any `.jmx` file from this directory.
3. (For data-driven tests) Ensure `data.csv` is in the same directory as the JMX file.
4. Click the green Start button (▶) to run the test plan.
5. View results in the included listeners (e.g., View Results Tree, Summary Report).

You can use these files as templates and modify endpoints, assertions, or data as needed for your own testing needs.
