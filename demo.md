# Demos

### Complete the following demos for PuppetConf Azure Talk:

1. Stand up a PE image in Azure with the Marketplace Image
  * Show Test Drive
  * Demonstrate Portal configurations
2. Add VMs to the Master via the Extension
  * Show custom facts
  * Show auto-signing capabilities
3. Add VMs to the Master via the Extension with Puppet Azure Module.
  * Optional
  * Show what's in the manifests
4. Deploy VM scale set template through Puppet Azure module that autoloadbalances the instances
  * Walk through VM Scale Sets
5. Generate synthetic load to get it to trigger autoscaling event.
  * Use artillery

artillery quick --duration 60 --rate 10 -n 20 http://kenazvmss4.westus.cloudapp.azure.com/
