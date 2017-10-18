```
The extensible ENUMERATION type simple_datum_reference_modifier may be used to modify a datum_reference_compartment or datum_reference_element when there is no value provided with the modifier.
Sentences are inconsistent….
TYPE datum_reference_modifier_type = EXTENSIBLE ENUMERATION OF     (circular_or_cylindrical,     spherical,     distance,     projected);    END_TYPE;  The extensible ENUMERATION type datum_reference_modifier_type is used when there is a value provided for the node in the tree structure and provides an assertion that the shape of the associated feature used to establish a datum is circular, cylindrical, spherical, two parallel planes, or a projected length as defined in ISO 5459.
<```