# ARM-Templates
To implement infrastructure as code for your Azure solutions, use Azure Resource Manager (ARM) templates. The template is a JavaScript Object Notation (JSON) file that defines the infrastructure and configuration for your project. The template uses declarative syntax, which lets you state what you intend to deploy without having to write the sequence of programming commands to create it. In the template, you specify the resources to deploy and the properties for those resources.

# It is:

1 Template-driven 
2. Declarative 
3. Idempotent 
4. Multi-service 
5. Multi region
6. Extensible 
#
# Template deployment types:
The ‘complete’ mode deletes any objects that do not appear in the template and the resource group you are deploying to. In this scenario, what you get is the ability to know that whenever you deploy you will be in exactly the same state.

The ‘incremental’ deployment uses the template to add additional resources to an existing resource group. The benefit of this is that you don’t lose any infrastructure that is missing from the template but the downside is that you will have to clear up any old resources some other way.

