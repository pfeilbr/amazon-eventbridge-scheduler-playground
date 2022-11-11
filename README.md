# amazon-eventbridge-scheduler-playground

learn [Introducing Amazon EventBridge Scheduler](https://aws.amazon.com/blogs/compute/introducing-amazon-eventbridge-scheduler/)

## General

- new service name `scheduler` (actions `scheduler:*`)


## Key features of EventBridge Scheduler


- Templated targets – EventBridge Scheduler supports templated targets to perform common API operations using Amazon SQS, Amazon SNS, Lambda, and EventBridge. With predefined targets, you can configure your schedules quickly using the EventBridge Scheduler console, the EventBridge Scheduler SDK, or the AWS CLI.
- Universal targets – EventBridge Scheduler provides a universal target parameter (UTP) that you can use to create customized triggers that target more than 270 AWS services and over 6,000 API operations on a schedule. With UTP, you can configure your customized triggers using the EventBridge Scheduler console, the EventBridge Scheduler SDK, or the AWS CLI.
- Flexible time windows – EventBridge Scheduler supports flexible time windows, allowing you to disperse your schedules and improve the reliability of your triggers for use cases that do not require precise scheduled invocation of targets.
- Retries – EventBridge Scheduler provides at-least-once event delivery to targets, meaning that at least one delivery succeeds with a response from the target. EventBridge Scheduler allows you to set the number of retries for your schedule for a failed task. EventBridge Scheduler retries failed tasks with delayed attempts to improve the reliability of your schedule and ensure targets are available.


### Differences between EventBridge Scheduler and EventBridge rules

![](https://www.evernote.com/l/AAEZYCpxKAlHhZv8BUR9HeV-z35mtfvHyYwB/image.png)

## Resources

- [Introducing Amazon EventBridge Scheduler](https://aws.amazon.com/blogs/compute/introducing-amazon-eventbridge-scheduler/)
- [Amazon EventBridge Scheduler - Launch Announcement](https://twitter.com/nickste/status/1590831305612488704?s=20&t=X2jVNzLdW5cRVrwocqCpQA) (twitter)
- [Scheduler User Guide](https://docs.aws.amazon.com/scheduler/latest/UserGuide/what-is-scheduler.html)