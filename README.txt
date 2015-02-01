Description

    internalExternalWorkflow is a product that adds a new workflow
    to a Plone 3.0.x site. It allows for content to be published:
    - for the world to see (external) by default
    - for all authenticated users (internal)
    - for select authenticated users are given view access
    - privately for only the owner and manager to see

Installation

    On the file system: place internalExternalWorkflow in the Products
    directory of your Zope instance and restart the server.

    In the Plone Web Interface: as portal manager, go to 'Portal > Site Setup
    > Add-on Products'.
    Select 'internalExternalWorkflow' and click the *Install* button.

    Uninstall -- Can be done from the same page.

Setting the workflow

    Workflow is set in the ZMI under portal_workflow. You can assign the
    workflow to individual items, or make it the default by entering at
    the bottom of the page.

Written by

    Paul Rentschler <paul@SurfsUpWebDesign.com>
