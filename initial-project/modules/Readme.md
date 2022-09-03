cfn init
>>m
>>MyCompany::S3::Bucket::MODULE
rm fragments/sample.json
cd fragments
nano s3-bucket.yaml
---
16\modules\s3-bucket.yaml

cd ..
cfn submit -v
---
creates a module in registry
template.yaml is using above module.
