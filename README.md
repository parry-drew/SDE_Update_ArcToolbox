# UpdateSDEFeature.ArcToolbox
These tools can be used to update features on an SDE. There are some assumptions made by the tools. This includes that you have admin rights on the SDE and that your replacement feature class has the same schema as the sde feature class.

### Update SDE Feature Single
The model will truncate and append a single SDE feature class and replace the records with another feature class. This model is helpful when updating individual features that may not have a consistent naming convention, but does have a consistent schema. The tool will also replace the metadata of the SDE feature class with the new feature class.

### Update SDE Feature Triple
This model is identical to Update SDE Feature Single, but it allows you the option of updating the same SDE feature on dev, qa, and prod in one go.
