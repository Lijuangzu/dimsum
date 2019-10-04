# dimsum
Just a repository
<?xml version='1.0' encoding='utf-8'?>
<designspace format="3">

    <!-- specify axes -->
    <axes>
        <!-- one axis for weight parameter that runs from 0 to 1000 with default location=0 -->
        <axis default="0" maximum="1000" minimum="0" name="weight" tag="wght" />
	</axes>

	<!-- specify masters -->
    <sources>

        <!-- first master, FamilyLight.ufo that sits on the weight axis on location=0 -->        
	<source familyname="Family" filename="FamilyLight.ufo" stylename="Light">
            <location>
                <dimension name="weight" xvalue="0" />
            </location>
        </source>

        <!-- second master, FamilyBold.ufo that sits on the weight axis on location=1000 -->
        <source familyname="Family" filename="FamilyBold.ufo" stylename="Bold">
            <location>
                <dimension name="weight" xvalue="1000" />
            </location>
        </source>
    
    </sources>

</designspace>
