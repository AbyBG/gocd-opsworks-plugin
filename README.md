This [GoCD](http://www.go.cd/) plugin manages deployment of [AWS OpsWorks](https://aws.amazon.com/opsworks/) applications.

## Installation
From Maven Central:
```xml
<dependency>
  <groupId>com.tispr.gocd</groupId>
  <artifactId>gocd-opsworks-plugin</artifactId>
  <version>0.0.3</version>
</dependency>
```

## Environment variables
- `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`
- `AWS_DEFAULT_REGION` - if not defined, default is us-east-1.

## Plugin Configuration

- App ID - OpsWorks App ID
- Stack ID - OpsWorks Stack ID
- Don't wait for deployment to finish - default, uncheck if waiting is required.

![Plugin preview](/docs/images/gocd-opsworks-plugin-preview.png)
![Plugin full view](/docs/images/gocd-opsworks-plugin-view.png)

# Credits
GoPluginBase implementation is based on reference implementations:
- https://github.com/gocd/go-plugins/tree/master/yum-plugin
- https://github.com/srinivasupadhya/script-executor-task
