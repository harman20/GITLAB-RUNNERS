# GITLAB-RUNNERS

It is a build intance which is used to run the jobs over multiple machines amd send results to Gitlab and which can be placed on separate users, servers and local machines. 

WE CAN SERVE OUR JOBS USING SPECIFIC OR SHARED RUNNERS.

1) SHARED RUNNERS-
These runners are useful for jobs multiple projects which have similar requirements. Instead of using multiple runners for many projects , we can use a single or small number of runners to handle multiple projects which will be easy to maintain and update.

2) SPECIFIC RUNNERS-
These runners are useful to deploy a certain project, if jobs have certain requirements or demands. SPECIFIC RUNNERS use FIFO process.



TRIGGERING PIPELINES-
Can force a specific branch or tag to get rebuilt with an API Call and triggers with legacy label.



