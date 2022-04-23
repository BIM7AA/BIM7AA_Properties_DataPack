# BIM7AA_Properties_DataPack

This property set includes Revit shared Parameters for BIM7AA parameters.

   * BIM7AA_PropertySet_V3.2.txt includes an IFC Propert Set for BIM7AA Type Codes
   * For Revit users BIM7AA_Shared Parameters_V3.2.txt includes Revit Shared Parameters BIM7AA Type Codes. The file also contains a useful selection of Shared Parameters ready to map to IFC Classes. BIM7AA does not define the usage of these IFC Classes but makes them available to standardize their use.

The BIM7AA excel spreadsheet for [BIM7AA Typecoding](http://www.bim7aa.dk/BIM7AA_Typekodning.html) includes mapping tables from BIM7AA to several other systems:

   * IFC2x3 TC1 CV2.0 - [Industry Foundation Classes IFC2x Edition 3 Technical Corrigendum 1](https://standards.buildingsmart.org/IFC/RELEASE/IFC2x3/TC1/HTML/) , [Coordination View 2.0](https://technical.buildingsmart.org/standards/ifc/mvd/mvd-database/)) 
   * IFC4 - [Industry Foundation Classes 4.0.2.1 Version 4.0 - Addendum 2 - Technical Corrigendum 1](https://standards.buildingsmart.org/IFC/RELEASE/IFC4/ADD2_TC1/HTML/)
   * CCS - [Cuneco Classification System (Danish)](https://molio.dk/produkter/digitale-vaerktojer/gratis-vaerktojer/ccs-cuneco-classification-system). CCS will be replaced in the future by [CCI Construction Classification International, (Danish)](https://molio.dk/produkter/digitale-vaerktojer/gratis-vaerktojer/cci). There is a [CCS - CCI mapping table (Danish, purchase)](https://anvisninger.molio.dk/aftale_og_kommunikation/mapping%20mellem%20ccs%20og%20cci)
   * FVK - [Forvaltning Klassifikation (Danish)](https://www.lbf.dk/publikationer/2014-forvaltnings-klassifikation/)
   * BC SfB - Samarbetskommitten for Byggnadsfragor, [SfB 1988 Bygningsdeltavle (Danish)](https://molio.dk/boeger/sfb-1988-bygningsdeltavle/c-23/p-2193), [description in english](https://www.designingbuildings.co.uk/wiki/CI/SfB), [Om SfB-systemet (Danish, PDF)](https://byg-erfa.dk/sites/default/files/attachments/om-sfb-systemet.pdf)

Keep in mind that mapping tables are never perfect as each classification system can contain different information and are organized in different ways.

## Building Parts Specification
The [Building Parts Specification from DiKon, BIM7AA and Molio](https://anvisninger.molio.dk/Gratis-vaerktojer/Bygningsdelsspecifikationer) is designed for specifiying a required LOIDK (Level og Information (DK)). For Revit users it includes an IFC export [BDS PropertySet configuration file](https://anvisninger.molio.dk/gratis-vaerktojer/bygningsdelsspecifikationer/bds_propertyset/bds_propertyset) for classification with BIM7AA, CCS, SfB and FVK. 

Many of the LOIDK properties described in the Building Parts Specification are found in the BIM7AA_Shared_Parameters Revit Shared Parameters file in this repository. To support [OpenBIM]() interoperability between software platforms these properties should be defining using the relevant IFC Classes.

There is some useful guidance on making a good IFC export, see [Revit setup for OpenBIM (OSArch page)](https://wiki.osarch.org/index.php?title=Revit_setup_for_OpenBIM), [IFC -Export Guide (EN) (buildingSMART Denmark)](https://anvisninger.molio.dk/Gratis-vaerktojer/buildingSMART/IFC_Export_Guide_EN) and [Exporting to Industry Foundation Classes (IFC) (Autodesk)](https://knowledge.autodesk.com/support/revit?sort=score&s=Exporting%20to%20Industry%20Foundation%20Classes%20(IFC)&page=1&p=RVT&p_disp=Revit)

