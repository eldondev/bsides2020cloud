* General outline of talk

1. What is cloud computing
	1. Who are the big players
	2. What do they do for you.
	3. How is it different from prior strategies.
	4. What are the high-level risks (exfil, misconfig, monitoring)
2. What are the common elements of cloud computing
	1. VMs
	2. Object Storage
	3. Networks
	4. Databases
	5. IAM
		1. How is this IAM different
		2. How did adding IAM to compute change that
		3. What are the new risks associated with IAM
3. Talk about types of breaches.
	1. Open S3 buckets
	2. Publicized cloud creds
	3. SSRF
	4. Dangling DNS
	5. Security Group misconfiguration
4. Cloud built-in monitoring capabilities:
	1. API call logs
	2. Billing logs
	3. Network logs
		1. Now with pcap!
5. Discuss CIS benchmarks
	1. What are CIS Benchmarks?
	2. What do they cover?
	3. Companies Utilizing CIS benchmarks
		1. Cloud Providers themselves
		2. Third party providers
		3. VARs
	4. OSS Tools that utilize CIS Benchmarks
6. Demos!
	1. Prowler
	2. ScoutSuite2
7. Bonus material for extra time!
	1. Using kubernetes to automate these tasks
	2. Sending output to ElasticSearch
8. Wrap-up, philosophy:
	1. Keeping up with the clouds
	2. Unifying the control plane
	3. What's next?
