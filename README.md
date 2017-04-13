Split a file that contains multiple certificates into separate PEM certificate files.

```
$ curl -sLRO 'https://pki.treas.gov/noca_fullpath.p7b'
$ ./split_certificates noca_fullpath.p7b 
cert.c3ebe3ec.0130.Federal_Common_Policy_CA.pem
cert.c3a58085.366E.US_Treasury_Root_CA.pem
cert.08ca0889.4E398116.NASA_Operational_CA.pem
cert.08ca0889.4A61D2A5.NASA_Operational_CA.pem
cert.08ca0889.45F94AB5.NASA_Operational_CA.pem
cert.08ca0889.443EA7E9.NASA_Operational_CA.pem
```
