# aws-ssh

A pure-python implementation of Amazon's Session Manager Client. It performs lookups for instance names and transforms them to an instance ID needed for starting a session. To do this, it reads the instance's `Name` tag.

## Usage:

### Start a CodeBuild with session manager
* https://docs.aws.amazon.com/codebuild/latest/userguide/session-manager.html

### 
```bash
python main.py codebuild:08318063-88e5-46cd-a23a-ebc873125f10
```
