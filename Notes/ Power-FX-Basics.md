# Key Power FX formulas and concepts

"Microsoft Power Fx is the new name for the formula language for canvas apps in Power Apps"

=="Makers== used to "describe a feature that might be used at either end of the programming skill spectrum."

"Developer" used to describe for users if the feature is more advanced and is likely beyond the scope of a typical Excel user."


reference: https://github.com/microsoft/power-fx

"Power Fx will be made available as open-source software."

"Power Fx as a formula language."

Excel formula: RIGHT(A1,LEN(A1)- FIND("|", SUBSTITUTE(A1," ","|", LEN(A1)-LEN(SUBSTITUTE(A1," ","")))) 

PowerFx formula: =RIGHT(Input.Text,Len(Input.Text)- FIND("|", SUBSTITUTE(Input.Text," ","|", Len(Input.Text)-Len(Substitute(Input.Text," ","")))) 