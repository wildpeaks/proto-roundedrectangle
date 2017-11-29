# RoundedRectangle

VRML PROTO (based on `IndexedFaceSet`) that **generates a rounded rectangle** geometry.

	EXTERNPROTO RoundedRectangle [
		exposedField  SFVec2f  size
		exposedField  SFFloat  border
		field         SFBool   solid
	] "proto.RoundedRectangle.wrl#RoundedRectangle"


-------------------------------------------------------------------------------

## Property `size`

**Width & height** of the inner area of the rounded rectangle.

You could use [MonospaceText.bboxSize](https://github.com/wildpeaks/proto-monospacetext#event-bboxsize)
to fit a tooltip around an arbitrary text.

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFVec3f`
 - Default Value: `2 2`


-------------------------------------------------------------------------------

## Property `border`

**Radius** of the rounded border of the rectangle.

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFVec3f`
 - Default Value: `1`


-------------------------------------------------------------------------------

## Property `solid`

Like `IndexedFaceSet.solid`, renders both sides (`FALSE`) or only the front side (`TRUE`).

Definition:
 - Field Type: `field`
 - Data Type: `SFBool`
 - Default Value: `TRUE`


-------------------------------------------------------------------------------

