## Structure

The structure of DataFactory is based on the _concept of the abstract factory_, a type of template for the development of solutions in software architecture and development.

The structure of DataFactory is subdivided into four layers with the abstract titles **Work, Factory, Product Line** and **Product**. Through the nonspecific labelling of the individual structural elements it is possible to illustrate the structure of diverse issues and applications and to design the desired system solutions. Because of this, DataFactory has a very broad usage spectrum and is flexible enough to meet diverse individual needs. 

The lowest level of the structure is the **product**. Data collection takes place on that level. Every product is based on a so-called template, on the basis of which further products are generated. The template can be understood as an abstract product in which only the structures and algorithms of a particular product type are defined. Many concrete products, i.e. products that carry concrete information, can be generated from one template.

Products are aggregated on a product line while product lines are aggregated on a factory level. The highest aggregation level is the **work**. 

The access rights can be assigned on the factory and product line levels, meaning that the user can only read and edit certain factory and product line information. This subject is further discussed in the chapter _**User Management**_.

Lists and formats are managed on the work level and can be implemented in all levels of the hierarchy. A more detailed description is given in the chapter _**Lists and Formats**_.

---

![](/assets/Struktur DF.png)

---



