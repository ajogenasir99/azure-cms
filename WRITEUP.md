# App Service v Virtual Machine

From my understanding, Azure Virtual Machines are an infrasture as a service while Azure app services are Platform as a service, VMs given its a Iaas gives a developer complete control over deployment and technology stack of the OS while App services is a paas which gives a developer less control over the deployment pipeline but is less time consuming and allows the developer to focus more on developing the app.
So from this i can analyze and compare the cost, scaliblity availability and workflow of these two services

## Cost Analysis

Generally VM are more expensive than App service since they provide more and heavier services than a typical App services, so in context of the CMS even though azure app service do not have a pay-as-you-go option, the App service makes more sense to use here.

## Scalability

App services are less scalable than VMs due to the hardware limitations whereas VMs generally are highly scalable and have no limit to the amount of VMs you can combine to support your software needs. For the CMS i don't think it's something that will need a lot of scalability so i will stick to the app services.

## availability

I'm not really sure which one is more available, you can make a case for the VMs being more available due to it's scalability advantage, but you can also make a case for azure app services as cost is also a significant factor when determining availability, cause something might be available in theory but the cost might mean in reality it really isn't, so i'd say this one is a tie.

## workflow

VMs are more time consuming and demands more attention as you'll need to pay attention to the entire VM, configuring it updating it e.t.c. and you still have to pay attention to your app, So i think the App service is preferable here for the CMS as it eliminates the work you'll have to do to maintain the VM.

# Conclusion

After taking into account everything i decided that the App service is the appropriate solution for deploying the app, my reasons are detailed above.

### Assess app changes that would change your decision.

_Detail how the app and any other needs would have to change for you to change your decision in the last section._

### Potential app changes that might affect my decision

The only reason i can think off that will make me choose a VM over a azure app services is

- Changing my app to a language not supported by azure app services
