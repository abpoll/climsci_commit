## Strict code openness
We commit to making all code for downloading data, processing data, running models, generating results, and producing figures and tables fully open, as well as findable and accessible with a unique identifier and in a persistent repository. This also entails using open-source programming languages whenever possible because they allow the broader community to recognize when bugs and biases in the base code may influence research results. Finally, we will not employ any code that can only be run by a small group due to model access restrictions in peer-reviewed journals. 

On this final point, we acknowledge that some peer-reviewed research on climate impacts employs limited license proprietary models that are used in current decision-making contexts (i.e. by utility companies). Researching the properties of these models is societally important because of its decision relevance. However, if a license is restrictive to the point that a broad audience cannot check that benchmarking or related analyses are reproducible, the study is not peer-reviewable and should be published outside the scientific peer-reviewed literature. A potentially productive alternative to the use of these models outside of peer-reviewed outlets is the development of open-source counterparts. 

## Genuine and traceable efforts for strict data openness
We commit to the following use cases:
1.	When raw data products are large[^1] (> 1 TB) and already available in a permanent archive, provide code for downloading raw data from the URL or API endpoint and share all output data for checking code correctness.
2.	When raw data products are large (> 1 TB) and not available in a permanent archive, conduct and document an effort to contact the data proprietor and have a version of the data posted to an appropriate repository. When the data proprietor does not oblige this request, either post the raw data to an appropriate repository or use a different raw data source.
3.	When raw data products are not public but accessible via license and/or payment, only incorporate this data into a research workflow if the following conditions are met:
a.	The data proprietor uses a license that allows for benchmarking, comparisons, and free use; and/or
b.	The data proprietor allows for a public release of a subset of this data such that the remaining workflow can be externally tested for reproducibility; and
c.	The data proprietor allows for a license user to provide detailed metadata documentation, a thorough description of quality assurance procedures, and share their raw data processing code so that external parties can procure data of the same, or similar, specification for related inquiries. 
4.	When raw data products are not public but accessible via license and/or payment, and none of the conditions in 3a or 3c are met, pursue publication in other outlets than peer-reviewed journals such as white papers or technical reports.
5.	When raw data products are procured under a confidentiality agreement or pertain to sensitive data with ethical or legal concerns, conduct and document an effort to employ methods with differential privacy or other anonymization techniques with the permission of required parties, such as an institutional review board and survey participants. When this is not possible, provide detailed metadata documentation, a thorough description of quality assurance procedures, and code that processes the raw data such that external parties can procure data of the same specification for related inquiries.
6.	When output data is large (>1 TB), it is acceptable to provide all code to produce outputs and a sample of the full workflow from raw to output data that allows for partial reproducibility checks. 

## Explicitly cite, in the main manuscript text, all datasets and software that is associated with a digital object identifier
We commit to citing the datasets and tools associated with a digital object identifier in the main manuscript text. This strengthens incentives for open data and code workflows and is a productive way to promote a culture of openness. It is crucial that developers of datasets and computational tools are given appropriate credit for their work.

## Write explicit and transparent data and code availability statements
We commit to improving the transparency and clarity of data and code availability statements. The first sentence of every data and code availability statement should indicate whether all, some, or none of the data and code is freely open in a unique and persistent repository. In addition, we will provide extensive details about what data is missing, what efforts were undertaken to procure the materials as fully open, and explicitly justify why a submission is sufficiently open for publication in a peer-reviewed outlet. 

## Write an explicit and transparent (p)reproducibility statement
We commit to writing explicit and transparent (p)reproducibility statements. In our view, since data and code openness are not sufficient for meeting scientific standards of reproducibility and replicability, authors need to convey more transparency about how reproducible a workflow is in addition to data and code openness statements. 

As reproduction checks and code peer-review are not often offered by climate change research journals, relying on colleagues who are not co-authors on a study to test (p)reproducibility is crucial. If journals begin to conduct reproduction checks, we will prioritize such journals for submission. In general, we are working to establish friendly-review processes to ensure that a workflow can be directly preproduced. We use “(p)reproducibility” to acknowledge that depending on the complexity of a project, it may be an unfair expectation of a colleague who does not get co-authorship credit to rerun a full analysis and perform tests for correctness. 

A (p)reproducibility statement serves to communicate to readers the extent to which an analysis has been tested for reproducibility. We commit to securing at least a preproducibility check, which often entails:
1)	Checking that all data and code is fully open; and
2)	Testing that a code environment configures correctly. For example, it is common for researchers who use python to define a conda environment that contains the exact versions of libraries used to perform a particular analysis; and
3)	Checking that there are instructions for reproducing the entire project analysis; and
4)	Checking that code is documented in a way that it is possible to follow how portions of an analysis are being conducted. 

Tools like Snakemake make these checks a normal part of the research production process[^2]. Adopting reproducibility frameworks like the meta repository framework from the Joint Global Change Research Institute[^3] can also make these checks a lighter load on colleagues. 

When it is not a major undertaking to test for reproducibility, we will ask colleagues to perform this more time-consuming and difficult check. For example, we are grateful to a colleague who performed a reproducibility check for the data processing and generation of summary statistics and figures underlying this paper. The colleague also provided notes about how we could improve the clarity of the reproducibility instructions included in our GitHub repository. Of course, “major” is subjective, which is why we aim to foster a culture of openness and reciprocity. 

When a (p)reproducibility check is done, an explicit and transparent account of the degree to which standards of preproducibility or reproducibility are met needs to be shared along with the main manuscript. In different contexts, (p)reproducibility may require different level of testing and checks, so it is important that the concept is defined for a particular analysis and the extent to which preproducibility and reproducibility are examined is conveyed clearly. For example, for studies where some data is not open due to license restrictions, a (p)reproducibility statement should articulate clearly if the person who conducted the (p)reproducibility check had access to the licensed data and was able to test that particular aspect of the workflow for (p)reproducibility.

## Be available to colleagues for (p)reproducibility checks for research we are not co-authors on
We commit to fostering a culture of reciprocity for openness and (p)reproducibility checks. Supervisors and mentors can play a substantial role in endorsing and demonstrating the importance of this responsibility. In addition, they can leverage their larger networks to provide these resources for mentees. 

## Evaluate credibility and impact conditioned on openness and (p)reproducibility
We commit to communicating the appropriate caution and uncertainty about the strength of evidence and claims in studies that are not fully open and have not been checked for (p)reproducibility. Relatedly, when citing studies that have been explicit and transparent about (p)reproducibility, we will reward authors for contributing to a culture of openness by citing their work, testing their work for reproducibility, and/or building on their work. Going forward, when reviewing articles for peer-reviewed journals that do not meet openness standards, we will recommend rejection to the editor. Similarly, we will not review for journals that do not systematically enforce openness standards and are not making transparent and strong efforts towards promoting needed scientific standards like reproducibility. Relatedly, when serving as a reviewer for funding proposals, we will carefully evaluate data management plans with the same attention to openness and reproducibility. These standards are also important to apply when serving on tenure review committees. 

[^1]: https://zenodo.org/records/5121489
[^2]: https://doi.org/10.12688/f1000research.29032.2
[^3]: https://zenodo.org/records/6646099


