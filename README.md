# RAP Booking Application

This is a demo project built using the **ABAP RESTful Application Programming Model (RAP)** in Eclipse ADT. It demonstrates how to build a transactional application using CDS Views, Behaviors, Business Services, and Fiori Elements.

## 🚀 Features

- CDS-based data model for booking management
- RAP-based managed scenario with behavior definitions
- UI annotations for Fiori preview
- Clean, extensible architecture
- Built and deployed via Eclipse ADT to an SAP S/4HANA system

## 🏗️ Project Structure

```bash
📁 zrap_booking_app/
├── data definitions (.asddls)
│   ├── zi_booking_hdr.asddls
│   └── zi_booking_items.asddls
├── behavior definitions (.behaviour)
├── metadata extensions (.ui)
├── service definition and binding
└── class-based logic (.abap)
```

### Key Components

- **CDS Views (`.asddls`)**: Defines the database model with annotations like `@UI.facet`, `@ObjectModel`, `@AccessControl`, etc.
- **Behavior Definitions**: Implements create/update/delete logic for transactional behavior.
- **Service Definition & Binding**: Exposes the CDS view and behavior as an OData service.
- **UI Annotations**: Define the layout and fields visible in the generated Fiori Elements app.

## 🔧 How to Run

1. **Import the Project into Eclipse ADT**  
   Open Eclipse with ADT and import the objects from this zip archive.

2. **Activate All Artifacts**  
   Activate the CDS views, behavior definitions, and services.

3. **Preview in Fiori Elements**  
   Use `Preview` option in Eclipse or `/n/IWFND/MAINT_SERVICE` in GUI to test the OData Service.

4. **Test CRUD Functionality**  
   Navigate through Fiori Elements preview to test creation, update, and deletion of booking records.

## 🛡️ Requirements

- SAP S/4HANA 1909 or later
- Eclipse ADT
- Developer access to an SAP system with RAP enabled

## 📚 References

- [SAP RAP Documentation](https://help.sap.com/viewer/product/ABAP_RESTful_Application_Programming_Model)
- [CDS Annotations](https://help.sap.com/docs/ABAP_PLATFORM)

---
