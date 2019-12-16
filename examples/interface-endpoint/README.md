## examples/interface-endpoint

Adding an interface endpoint to a VPC for an AWS service eliminates the data transfer costs to use that service but 
instead incurs a cost for adding ENIs in each subnet.  For this reason interface endpoints are not enabled by default.

This example shows how to extend the VPC module to add an interface endpoint