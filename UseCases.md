Use case 1: Identify spectra for proteins.
In this use case, I would want to know which spectra support a given protein. I would query in with an identifier and expect back the dataset accession, file, and spectrum number of supporting proteins. I imagine that such an API would be useful to Uniprot, or potentially already exists - SHP

Use Case 2: Identify spectra for a set of protein orthologs
In this use case, I would want to query with a single protein, have the API find orthologs in other species and then return spectra which correspond to all the orthologous proteins - SHP

Use Case 3: PTMs for proteins
This use case is a lot like #1, but with the ability to narrow by PTM. For a given PTM and protein, return all relevant spectra. - SHP

Use case 4: Gather data for machine learning
In this use case, the user specifies parameters on the type and quality of spectra (orbi, MS/MS res>15,000, q< 0.0001) and then asks for all passing spectra. Ideally this would actually create a new mgf or some spectral file. Otherwise it's a ton of work to parse all these out from the various original .RAW files. - SHP
