# severless-spring-cloud-function

video tutorial: [Serverless Spring: Deploy serverless functions to any platform using Spring Cloud Function](https://www.youtube.com/watch?v=gj1DDymw5iY)

tutorial guide: [Serverless Spring](https://tanzu.vmware.com/developer/guides/serverless-spring/)

## Severless - What, When & Why

If you’re building solutions for the web chances are you have heard the term Serverless before, but what does it really mean? If you have experience deploying applications you know how to package an entire application and push it to a server somewhere. This could be in your own on-prem data center or a server in the Cloud. In most cases this server was provisioned by someone to handle that application you have deployed.

In a serverless world, or at least the one we are discussing today you aren’t dealing with an entire applications and instead focused on individual functions. This is why you will often hear serverless referred to as serverless functions or Functions as a Service (FaaS). As you have probably already guessed there are servers involved, the serverless part in the name just implies that you don’t have to provision them or care about who has.

Now that you have an idea of what a serverless function is lets talk about when you might want to reach for serverless functions. In a traditional application that you have deployed you might be taking requests and returning responses all day long. In those situations it makes sense to host your application on a server that is always up and always waiting for requests.

What happens in a scenario where you aren’t taking requests all day? Let’s say you created a new landing page for a newsletter that you started. On this landing page subscribers could sign up to receive your weekly newsletter by entering their email address and clicking the sign-up button. I currently have about 4,000 subscribers on my newsletter and at best get about 5 new subscribers per day. In this situation does it really make sense to pay for a server to be running all day long to handle 5 requests?

The answer to this no and its a perfect use case for moving this functionality to serverless functions. This isn’t the only reason why to reach for serverless though, it has many features:

- Scalability: Serverless functions can be auto provisioned to scaled depending on load. This means that if your newsletter gets really popular you can be confident that the service will be able to handle the increase in traffic.
- Cost: When it comes to serverless you only pay for what you use. This means that while your functions are not being used and just sitting idle you are not paying for them. 
- Security: Serverless platforms are patching your systems and runtimes on your behalf and this is one less thing you need to manage.

You just saw one good use case for serverless but we want to leave you with a few others that might peak your curiosity:

- Full Application (Static Site + BaaS)
- Backend as a Service (BaaS)
- REST API
- Authentication
- Multimedia Transformation
- Email Notification
- Data Transformation
- CRON Jobs
