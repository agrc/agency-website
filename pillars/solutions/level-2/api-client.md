# API client

The Utah Geospatial Resource Center (UGRC) is the State of Utah’s map technology coordination office. The UGRC creates, maintains, and stores geospatial data in the State Geographic Information Database (SGID), a one-stop shop to hundreds of data layers developed, aggregated, or acquired by state government. UGRC’s Web API is an http-enabled service for accessing this valuable geospatial data.

From querying any data layer in the SGID to geocoding addresses against the most accurate statewide roads dataset, the application of the API is endless. The API also powers UGRC’s widgets, toolboxes, and add-ins, which can help you navigate the sea of data in the SGID.

The UGRC API Client is an app to help make geocoding addresses simple. This app allows the user to use the UGRC API without any licensed software or programming knowledge; Drag and drop a file and then click start.

Check out our introductory blog post and our getting started video.

- Introduce the API client and other ways to access the web services
- Introductory blog post
- introductory video
- talk about documentation
- give examples

## Development Specifics

### Certificates


An apple developer certificate is required to sign the application for distribution.

Using keychain's certificate assistant, request a certificate from a certificate authority.
Leave CA Email address empty
Request is Saved to diskProvide the certificate request to Certificates, Identifiers & Profiles to create a Developer ID Certificate
Only the account holder of the Developer Group can create this type of certificate.
Import the certificate to keychain and then export it as a p12 file for the deployment pipeline.
Store the password required for exporting for the GitHub Actions secrets.
