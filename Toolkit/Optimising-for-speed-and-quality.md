# Speed and Quality

## Speed = Cycle time & Deployment Frequency

**Cycle time** = is a measure from the moment work starts to work being completed, by optimising for a low cycle time (_typically high performing teams have a cycle time of 24 hours_) then work is inevitably smaller, smaller changes are easier to review, easier to test and easier to deploy - reducing the impact of a big bang. Smaller releases means any failure can be identified and fixed more quickly e.g. rollback or fix forward. 

Other variants of this metric include lead time - the time from story creation to work being completed and this includes the time an item is sat in a backlog, e.g. includes refinement and waiting time. Cycle Time can also be the time work is started (first commit) to PR being created, however, using Azure DevOps we'll use their ticket cycle time as a proxy. 

**Deployment frequency**  = in order to push to production (_and high performing teams do this on demand multiple times a day [if the business can accept]_). Optimising for deployments means work has to be smaller to get the approval. The more often we deploy the quicker we are to add value for our customers, by releasing often we reduce the mean time to restore as we can easily deploy again a fix.

## Quality = Change Failure Rate & Mean Time To Restore

**Change failure rate** = is a measure of how often a deployment results in an incident, that is a degradation of service such that our users cannot perform the outcome intended, this isn't the same as a bug. We measure this as a percentage of deployments that have failed _and high performing teams have a change failure rate of less than 3%_ - By optimising for low change failure rate (or **CFR**) we end up with more deployments. A once a year deployment encompassing 12 months of changes has a much greater risk of failure and would be 100%. By increasing the number of deployments to say 26.. say once a sprint.. then the percentage for that one breaking change is 1/26 or 3.84% but if we do get to multiple deployments a day so 700 a year ish, that becomes 0.143% and elite!

**Mean time to restore** = is a measure in hours of how long it takes to restore the service to a working state. _High performing teams typically restore within an hour_. Optimising for ***MTTR*** means having a strong CI/CD pipeline and the ability to revert a deployment, it's a lot easier to revert a deployment when the change is smaller, reducing the impact on our customers. So by trying to optimise for restoration we value having a smaller deployment.

> Quality is everyone's responsibility - W. Edwards Deming
