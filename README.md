# amazon-aws

Bucket-name-->myfirstbucket-dilip
Topic-name--> dilip_topic
cloudhub log_message:--->

13:36:38.842     11/17/2019     Deployment     system     SYSTEM
Application queued to be deployed...
13:36:39.816     11/17/2019     Deployment     system     SYSTEM
Deploying application to 1 workers in us-east-2 region(s).
13:36:40.394     11/17/2019     Deployment     system     SYSTEM
Provisioning CloudHub worker in region=us-east-2...
13:36:40.973     11/17/2019     Deployment     system     SYSTEM
Starting CloudHub worker at 3.16.164.100 ...
13:36:56.873     11/17/2019     Deployment     system     SYSTEM
Worker(3.16.164.100): Starting your application on mule=4.2.1...
13:36:59.014     11/17/2019     Worker-0     qtp901732639-37     INFO
The PersistentQueueManager is NOT configured. The normal VM queue manager will be used.
13:37:05.998     11/17/2019     Worker-0     qtp901732639-37     INFO
Loaded MuleMessageBuilderFactory implementation 'org.mule.runtime.core.internal.message.DefaultMessageBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@5de3b18b'
13:37:06.045     11/17/2019     Worker-0     qtp901732639-37     INFO
Loaded BindingContextBuilderFactory implementation 'org.mule.runtime.core.api.el.DefaultBindingContextBuilderFactory' from classloader 'org.mule.runtime.module.reboot.internal.MuleContainerSystemClassLoader@5de3b18b'
13:37:06.805     11/17/2019     Worker-0     qtp901732639-37     INFO
Using files for tx logs /opt/mule/mule-4.2.1/./.mule/aws-s3-connect/queue-tx-log/tx1.log and /opt/mule/mule-4.2.1/./.mule/aws-s3-connect/queue-tx-log/tx2.log
13:37:06.813     11/17/2019     Worker-0     qtp901732639-37     INFO
Using files for tx logs /opt/mule/mule-4.2.1/./.mule/aws-s3-connect/queue-xa-tx-log/tx1.log and /opt/mule/mule-4.2.1/./.mule/aws-s3-connect/queue-xa-tx-log/tx2.log
13:37:07.396     11/17/2019     Worker-0     qtp901732639-37     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_S3_Configuration1
13:37:07.527     11/17/2019     Worker-0     qtp901732639-37     INFO
Initialising Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config
13:37:07.871     11/17/2019     Worker-0     qtp901732639-37     INFO
Initialising flow: awsreFlow
13:37:07.949     11/17/2019     Worker-0     qtp901732639-37     INFO
Initialising Bean: listener
13:37:08.038     11/17/2019     Worker-0     qtp901732639-37     INFO
Initialising flow: aws_s3Flow
13:37:08.039     11/17/2019     Worker-0     qtp901732639-37     INFO
Initialising Bean: listener
13:37:08.062     11/17/2019     Worker-0     qtp901732639-37     INFO
Initialising flow: aws_s3Flow1
13:37:08.064     11/17/2019     Worker-0     qtp901732639-37     INFO
Initialising Bean: listener
13:37:08.245     11/17/2019     Worker-0     qtp901732639-37     INFO
Persistent queues is not enabled for batch module as it was not configured in Cloudhub console
13:37:08.268     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting ResourceManager
13:37:08.268     11/17/2019     Worker-0     qtp901732639-37     INFO
Started ResourceManager
13:37:08.274     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-Amazon_S3_Configuration1
13:37:09.040     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting Bean: org.mule.runtime.module.extension.internal.runtime.config.ConfigurationProviderToolingAdapter-HTTP_Listener_config
13:37:09.058     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting flow: awsreFlow
13:37:09.232     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting flow: aws_s3Flow
13:37:09.235     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting flow: aws_s3Flow1
13:37:09.248     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting Bean: listener
13:37:09.251     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting Bean: listener
13:37:09.265     11/17/2019     Worker-0     qtp901732639-37     INFO
Starting Bean: listener
13:37:09.269     11/17/2019     Worker-0     qtp901732639-37     INFO

**********************************************************************
* Application: aws-s3-connect                                        *
* OS encoding: UTF-8, Mule encoding: UTF-8                           *
*                                                                    *
**********************************************************************
13:37:09.598     11/17/2019     Deployment     system     SYSTEM
Worker(3.16.164.100): Your application has started successfully.
13:37:10.262     11/17/2019     Deployment     system     SYSTEM
Your application is started.
