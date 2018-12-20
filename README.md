# CVS-claim
BRMD upload and Test-Bed generation


Test Run procedure:

BRMD upload:

java -DMy_Bserv_Username=439042  -DMy_Bserv_Password=******* -DMy_BRMD_Path="C:\Users\736085\Desktop\30oct\CommunityCare Health of OK BRMD v51_7nov_v2.xlsm" -DMy_Plan_ID=MRX64S2M3 -DTest_To_Run="upload brmd" -Dcareer_Code="2474" -Daccount_Code=B -Dgroup_Code=C01879HD05 -DCag_Type= -Doverride_Plan_Code= -Dded_Ind_Details="$3000" -Dded_Fam_Details="6000" -Dmoop_Ind_Details="4500" -Dmoop_Fam_Details="9000" -DMy_Plan_Type="exchange"  -jar cvs-b-ser-0.0.4.jar 




Test Bed generation:

java -DMy_Bserv_Username=439042  -DMy_Bserv_Password=****** -DMy_BRMD_Path="C:\Users\736085\Desktop\30oct\CommunityCare Health of OK BRMD v51_7nov_v2.xlsm" -DMy_Plan_ID=MRX64S2M3 -DTest_To_Run="test bed generation" -Dcareer_Code="2474" -Daccount_Code=B -Dgroup_Code=C01879HD05 -DCag_Type= -Doverride_Plan_Code= -Dded_Ind_Details="$3000" -Dded_Fam_Details="6000" -Dmoop_Ind_Details="4500" -Dmoop_Fam_Details="9000" -DMy_Plan_Type="exchange"  -jar cvs-b-ser-0.0.4.jar
