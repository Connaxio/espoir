The original file can be found here: https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2

Guide to the CERN-OHL-W v2
==========================
This document contains guidelines on how to apply the CERN-OHL-W v2 to a given hardware design, and on the use of hardware designs licensed under the CERN-OHL-W v2.

How to apply the CERN-OHL-W v2 to a hardware design
---------------------------------------------------
Pre-requisite:
--------------
Authorship/ownership of the design must be clear and undisputed. Only the legal owner of the rights in the hardware design may decide under what conditions to make it available. If ownership is vested in more than one person/entity, there must be an agreement among the owners (or a chain of compatible licences from each of them) to release the hardware design as open hardware, and under the CERN-OHL-W v2 in particular.
The hardware design source package
Pack all your hardware design Source files (e.g. for a Printed Circuit Board schematics, layout, documentation...) as well as the documents listed below in an archive file. This will ensure the licensee downloads everything in one go. It is best to archive the files using a format everybody can open. Schematics and layouts should be included in both source form and, should the design tool be proprietary, a format readable by everybody, such as pdf.
The following documents must be distributed together with the hardware design sources:
    • Document containing the CERN-OHL-W v2
    • This Guide
    • A text file (plain ASCII file), where information can be added to but not removed from,  noting that the design has been changed, and providing a date and information about the changes made by Licensee (see section 3.3.b of CERN-OHL-W v2) (e.g. CHANGES.TXT). A detailed list of changes would be helpful, as would a diff, but a description of the changes (e.g. “AC/DC power converter circuit removed as AC input no longer necessary”) is fine.


What to do with the hardware design sources
-------------------------------------------
Include in the hardware design sources, for instance as a header, the following elements:
    • a copyright notice reflecting actual ownership;
    • a notice that the hardware design source is licensed under the CERN-OHL-W v2, possibly with a link to https://cern.ch/cern-ohl :
        ◦ “Licensed under CERN-OHL-W v2 or later”
        ◦ “Licensed under CERN-OHL-W v2”;
    • a disclaimer of warranties;
    • a Source Location if you wish to specify one;
    • optionally, a Notice specifying that you wish the Source Location to remain visible on the Product (or its packaging, or in its documentation) even after modifications.
The following is an example of header if CERN is the Licensor:

> Copyright CERN 2020.
> This source describes Open Hardware and is licensed under the CERN-OHL-W v2
> You may redistribute and modify this documentation and make products using it under the terms of the CERN-OHL-W v2 (https:/cern.ch/cern-ohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-W v2 for applicable conditions.
> Source location: https://www.ohwr.org/project/wr-switch-hw
> As per CERN-OHL-W v2 section 4.1, should You produce hardware based on these sources, You must maintain the Source Location visible on the external case of the White Rabbit switch or other product you make using this documentation.

Include in a part of the Source corresponding to a visible part of the Product (e.g. silkscreen or top copper for a Printed Circuit Board):
    • the licence notice: “Licensed under CERN-OHL-W v2”
        ◦ Do not include the CERN logo or the copyright notice
    • the Source Location if you wish it to appear on the Product, its packaging or documentation, thus enabling all subsequent recipients of the Products to find the Sources.

How to deal with hardware designs licensed under the CERN- OHL-W v2
-------------------------------------------------------------------
Generally speaking, you must always comply with any obligations applying to a particular design (detailed in a contract or accompanying licence). If you receive hardware designs licensed under the CERN-OHL-W v2, the obligations are to:
    • Keep intact all the copyright and trademark notices and Source Location notices that are on the hardware design sources;
    • Keep intact the references to the CERN-OHL-W v2;
    • Keep intact the disclaimer of warranties.
If you modify hardware design that you received from someone else that is licensed under the CERN-OHL-W v2, you must
    • Keep intact all the notices referred to above, although you may remove notices that are no longer relevant to your design (for example, if the design you are using contains a power supply and a processor board, and you are only using the processor board in your own design, you can remove the notices relating to the power supply, so long as you are sure they only relate to the power supply);
    • Include notices that you have modified the hardware designs, giving a date and information about the modifications you have made (e.g. in a CHANGES.TXT file);
    • Add the appropriate copyright notice and Source Location to the modifications that were made;
    • license the modifications under the CERN-OHL-W v2 if you distribute them.
