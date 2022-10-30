 [<<< Back to index page](README.md)

# New fastener creation guide.

This guide describes the process of creating a new fastener if this type of fastener already exists in the workbench. If you want to create a completely new type of fastener that is not present in the workbench, then you need to refer to another guide. 

Typical process of fastener creation from code illustrated on this picture:

typical function (on the example of creating a screw) must be do follow actions:

1. Load data from *.csv tables.

2. Build contour (profile).

3. Create solid body by revolve contour.

4. Adding a head recess (slot).

5. Adding a realistic screw thread if thread attribute is equal true.

Creation of more difficult fastener may include more operations. For example hexogonal screw head needs more operations to create.
