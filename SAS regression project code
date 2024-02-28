/* Generated Code (IMPORT) */
/* Source File: Fall 2023 Lab #3 Closing Prices.xlsx */
/* Source Path: /home/u63542550/sasuser.v94 */
/* Code generated on: 11/21/23, 12:10 PM */

%web_drop_table(WORK.IMPORT);


FILENAME REFFILE '/home/u63542550/sasuser.v94/Fall 2023 Lab #3 Closing Prices.xlsx';

PROC IMPORT DATAFILE=REFFILE
	DBMS=XLSX
	OUT=WORK.stock;
	GETNAMES=YES;
RUN;

PROC CONTENTS DATA=WORK.stock; RUN;


%web_open_table(WORK.IMPORT);

proc print data = stock (OBS=10); run;
/* ACN ADBE AKAM AMD APH */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = ACN/legendlabel="ACN";
	series x = date y = ADBE/legendlabel="ADBE";
	series x = date y = AKAM/legendlabel="AKAM";
	series x = date y = AMD/legendlabel="AMD";
	series x = date y = APH/legendlabel="APH";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and First 5 Potential Independent Variables";
RUN;
/* ADI ANSS AAPL AMAT ANET*/
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = ADI/legendlabel="ADI";
	series x = date y = ANSS/legendlabel="ANSS";
	series x = date y = AAPL/legendlabel="AAPL";
	series x = date y = AMAT/legendlabel="AMAT";
	series x = date y = ANET/legendlabel="ANET";
	title "Scatter Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
/* ADSK AVGO CDNS CDW CSCO */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = ADSK/legendlabel="ADSK";
	series x = date y = AVGO/legendlabel="AVGO";
	series x = date y = CDNS/legendlabel="CDNS";
	series x = date y = CDNS/legendlabel="CDW";
	series x = date y = CSCO/legendlabel="CSCO";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
/*CTSH GLW ENPH EPAM FFIV*/
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = CTSH/legendlabel="CTSH";
	series x = date y = GLW/legendlabel="GLW";
	series x = date y = ENPH/legendlabel="ENPH";
	series x = date y = EPAM/legendlabel="EPAM";
	series x = date y = FFIV/legendlabel="FFIV";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
/*FICO FSLR FTNT IT GEN */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = FICO/legendlabel="FICO";
	series x = date y = FSLR/legendlabel="FSLR";
	series x = date y = FTNT/legendlabel="FTNT";
	series x = date y = IT/legendlabel="IT";
	series x = date y = GEN/legendlabel="GEN";
	yaxis label="Price of Share";
	title "Scatter Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
/* HPE HPQ IBM INTC INTU */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = HPE/legendlabel="HPE";
	series x = date y = HPQ/legendlabel="HPQ";
	series x = date y = IBM/legendlabel="IBM";
	series x = date y = INTC/legendlabel="INTC";
	series x = date y = INTU/legendlabel="INTU";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
/* JNPR KEYS KLAC LRCX MCHP  */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = JNPR/legendlabel="JNPR";
	series x = date y = KEYS/legendlabel="KEYS";
	series x = date y = KLAC/legendlabel="KLAC";
	series x = date y = LRCX/legendlabel="LRCX";
	series x = date y = MCHP/legendlabel="MCHP";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
/*  MU MSFT MPWR MSI NVDA   */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = MU/legendlabel="MU";
	series x = date y = MSFT/legendlabel="MSFT";
	series x = date y = MPWR/legendlabel="MPWR";
	series x = date y = MSI/legendlabel="MSI";
	series x = date y = NVDA/legendlabel="NVDA";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
/*  NXPI ON ORCL PANW PTC */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = NXPI/legendlabel="NXPI";
	series x = date y = ON/legendlabel="ON";
	series x = date y = ORCL/legendlabel="ORCL";
	series x = date y = PANW/legendlabel="PANW";
	series x = date y = PTC/legendlabel="PTC";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
	/*QRVO QCOM ROP CRM STX */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = QRVO/legendlabel="QRVO";
	series x = date y = QCOM/legendlabel="QCOM";
	series x = date y = ROP/legendlabel="ROP";
	series x = date y = CRM/legendlabel="CRM";
	series x = date y = STX/legendlabel="STX";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
	/*NOW SWKS SEDG SNPS TEL */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = NOW/legendlabel="NOW";
	series x = date y = SWKS/legendlabel="SWKS";
	series x = date y = SEDG/legendlabel="SEDG";
	series x = date y = SNPS/legendlabel="SNPS";
	series x = date y = TEL/legendlabel="TEL";
	yaxis label="Price of Share";
	title " Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
	/*TDY TER TXN TRMB TYL */
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = TDY/legendlabel="TDY";
	series x = date y = TER/legendlabel="TER";
	series x = date y = TXN/legendlabel="TXN";
	series x = date y = TRMB/legendlabel="TRMB";
	series x = date y = TYL/legendlabel="TYL";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;
	/*VRSN WDC ZBRA*/
proc sgplot data=stock;
	series x = date y = NTAP/legendlabel="NTAP";
	series x = date y = VRSN/legendlabel="VRSN";
	series x = date y = WDC/legendlabel="WDC";
	series x = date y = ZBRA/legendlabel="ZBRA";
	yaxis label="Price of Share";
	title "Plot of Prices Over Time for Dependent variable and Next 5 Potential Independent Variables";
RUN;

/*proc corr to get a strating point */
proc corr data=stock;
	var NTAP;
	with ACN ADBE AKAM AMD APH 
	ADI ANSS AAPL AMAT ANET 
	ADSK AVGO CDNS CDW CSCO 
	CTSH GLW ENPH EPAM FFIV 
	FICO FSLR FTNT IT GEN 
	HPE HPQ IBM INTC INTU 
	JNPR KEYS KLAC LRCX MCHP 
	MU MSFT MPWR MSI NVDA 
	NXPI ON ORCL PANW PTC 
	QRVO QCOM ROP CRM STX 
	NOW SWKS SEDG SNPS TEL 
	TDY TER TXN TRMB TYL 
	VRSN WDC ZBRA; 
	run;
/*proc corr with all potential varibles to get graphs*/
proc corr data=stock;
	var NTAP;
	with ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC;
	run;
/*1-5 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with ACN ADBE AKAM AMD APH;
	run;
/*6-10 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with AAPL AMAT ANET ADSK AVGO;
	run;
/*11-15 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with CDNS CSCO CTSH ENPH EPAM;
	run;
/*16-20 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with FFIV FICO IT HPE INTC; 
	run;
/*21-25 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with INTU JNPR KEYS KLAC LRCX;
	run;
/*26-30 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with MU MSFT MPWR NVDA NXPI; 
	run;
/*31-35 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with ON ORCL PANW PTC ROP; 
	run;
/*36-40 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with CRM NOW SEDG SNPS TEL; 
	run;
/*41-42 graphs*/
proc corr data=stock plots=scatter(nvar = all);
	var NTAP;
	with TYL WDC; 
	run;
	
/*multiple Regression*/
/*STEPWISE*/
proc reg data=stock;
	model NTAP=ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC/selection=stepwise SLENTRY=0.05;
	run; 
	
/*STEPWISE MODEL*/
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV FICO INTU JNPR 
	LRCX MU ON ORCL PANW 
	ROP CRM NOW SEDG TEL;
	run;

/*FORWARD*/
proc reg data=stock;
	model NTAP=ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC/selection=forward SLENTRY=0.05;
	run; 

/*FORWARDS MDOEL*/
proc reg data=stock;
	model NTAP=ACN JNPR TEL AKAM FICO 
	PANW SEDG MU MSFT INTU 
	CRM ENPH CTSH ORCL AMD 
	ON ANET FFIV AMAT ADSK 
	ROP NOW TYL;
	run;

/*BACKWARD*/
proc reg data=stock;
	model NTAP=ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC/selection=backward SLENTRY=0.05;
	run;
	
/*BACKWRDS MODEL*/
proc reg data=stock;
	model NTAP=AKAM AMD APH AAPL AMAT 
	ANET ADSK ENPH FFIV FICO 
	INTC INTU JNPR MU MSFT 
	NXPI ON ORCL PANW ROP
	CRM NOW SEDG SNPS TEL 
	TYL;
	run;

/*R^2*/
proc reg data=stock;
	model NTAP=ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC/selection=rsquare;
	run; 
	
/*r^2 MODEL*/
proc reg data=stock;
	model NTAP = ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC;
   	RUN;

/*ADJ R^2 */
proc reg data=stock;
	model NTAP=ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC/selection=adjrsq;
	run; 
	
/* ADJ R^2 MODEL */
proc reg data=stock;
	model NTAP = ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	ENPH FFIV FICO IT INTC 
   	INTU JNPR MU MSFT NXPI 
   	ON ORCL PANW ROP CRM 
   	NOW SEDG SNPS TEL TYL;
   	RUN;

/*cp*/
proc reg data=stock;
	model NTAP=ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC/selection=cp;
	run;
	
/* CP MODEL */
proc reg data=stock;
	model NTAP=AKAM AMD AAPL AMAT ANET 
	ADSK AVGO ENPH FFIV FICO 
	INTU JNPR KEYS MU NXPI 
	ON ORCL PANW PTC ROP 
	CRM NOW SEDG SNPS TEL 
	TYL WDC;
	run; 

/*press*/
proc glmselect data=stock;
	model NTAP=ACN ADBE AKAM AMD APH 
   	AAPL AMAT ANET ADSK AVGO 
   	CDNS CSCO CTSH ENPH EPAM 
   	FFIV FICO IT HPE INTC 
   	INTU JNPR KEYS KLAC LRCX 
   	MU MSFT MPWR NVDA NXPI 
   	ON ORCL PANW PTC ROP 
   	CRM NOW SEDG SNPS TEL 
   	TYL WDC/selection=stepwise (choose=press);
	run;
	
/* PRESS MODEL*/
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK AVGO 
	ENPH FFIV FICO INTU JNPR 
	LRCX MU ON ORCL PANW 
	ROP CRM NOW SEDG TEL;
	run; 

/* best model from stepwise*/
/*test for multicolinearity*/
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV FICO INTU JNPR 
	LRCX MU ON ORCL PANW 
	ROP CRM NOW SEDG TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV FICO INTU JNPR 
	MU ON ORCL PANW ROP 
	CRM NOW SEDG TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV FICO INTU JNPR 
	MU ON ORCL PANW 
	ROP CRM SEDG TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV INTU JNPR 
	MU ON ORCL PANW 
	ROP CRM SEDG TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV JNPR 
	MU ON ORCL PANW 
	ROP CRM SEDG TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV JNPR 
	MU ON ORCL PANW 
	ROP SEDG TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV JNPR 
	MU ON ORCL PANW 
	ROP TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV JNPR 
	MU ON PANW 
	ROP TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV JNPR 
	MU PANW 
	ROP TEL/vif;
	run;
/* took out highest vif value over 10 */
proc reg data=stock;
	model NTAP=AKAM AMD ANET ADSK 
	ENPH FFIV JNPR 
	MU PANW TEL/vif;
	run;
/*take out insignifigant indep vars*/
/*model after taking out insignifigant terms and terms causing issues with multicolinearity*/
proc reg data=stock;
	model NTAP=AKAM AMD ENPH JNPR 
	MU PANW TEL/vif;
	run;

/*quad terms*/
proc sgplot data=STOCK;
   scatter x=akam y=NTAP;
run;

proc sgplot data=stock;
   scatter x=amd y=NTAP;
run;
	
proc sgplot data=STOCK;
   scatter x=enph y=NTAP;
run;

proc sgplot data=stock;
   scatter x=jnpr y=NTAP;
run;

proc sgplot data=STOCK;
   scatter x=mu y=NTAP;
run;

proc sgplot data=stock;
   scatter x=panw y=NTAP;
run;

proc sgplot data=stock;
   scatter x=tel y=NTAP;
run;
/*enph, jnpr, mu looks like potential quad terms*/

/*interaction terms*/
/*AKAM*/
proc glm data=stock;
 model ntap=akam | amd / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=akam sliceby=amd);
run;

proc glm data=stock;
 model ntap=akam | enph / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=akam sliceby=enph);
run;

proc glm data=stock;
 model ntap=akam | JNPR / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=akam sliceby=JNPR);
run;

proc glm data=stock;
 model ntap=akam | MU / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=akam sliceby=MU);
run;

proc glm data=stock;
 model ntap=akam | PANW / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=akam sliceby=PANW);
run;

proc glm data=stock;
 model ntap=akam | TEL / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=akam sliceby=TEL);
run;
/*AMD*/
proc glm data=stock;
 model ntap=AMD | ENPH / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=AMD sliceby=ENPH);
run;

proc glm data=stock;
 model ntap=AMD | JNPR / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=AMD sliceby=JNPR);
run;

proc glm data=stock;
 model ntap=AMD | MU / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=AMD sliceby=MU);
run;

proc glm data=stock;
 model ntap=AMD | PANW / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=AMD sliceby=PANW);
run;

proc glm data=stock;
 model ntap=AMD | TEL / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=AMD sliceby=TEL);
run;

/*ENPH */
proc glm data=stock;
 model ntap=ENPH | JNPR / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=ENPH sliceby=JNPR);
run;

proc glm data=stock;
 model ntap=ENPH | MU / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=ENPH sliceby=MU);
run;

proc glm data=stock;
 model ntap=ENPH | PANW / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=ENPH sliceby=PANW);
run;

proc glm data=stock;
 model ntap=ENPH | TEL / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=ENPH sliceby=TEL);
run;
/*JNPR*/
proc glm data=stock;
 model ntap=JNPR | MU / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=JNPR sliceby=MU);
run;

proc glm data=stock;
 model ntap=JNPR | PANW / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=JNPR sliceby=PANW);
run;

proc glm data=stock;
 model ntap=JNPR | TEL / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=JNPR sliceby=TEL);
run;
/*MU*/
proc glm data=stock;
 model ntap=MU| PANW / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=MU sliceby=PANW);
run;

proc glm data=stock;
 model ntap=MU | TEL / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=MU sliceby=TEL);
run;
/*PANW */
proc glm data=stock;
 model ntap=PANW | TEL / solution;
 store GLMModel;
 run;

proc plm restore=GLMModel noinfo;
   effectplot slicefit(x=PANW sliceby=TEL);
run;
/*TEL ALL ALREADY GRAPHED*/
/*new set with quad and interaction terms*/
Data stock2;
	set stock;
	ENPHSQ = ENPH*ENPH;
	JNPRSQ = JNPR*JNPR;
	MUSQ = MU*MU;
	AKAM_ENPH = AKAM*ENPH;
	AKAM_JNPR = AKAM*JNPR;
	AKAM_PANW = AKAM*PANW;
	AMD_ENPH = AMD*ENPH;
	AMD_JNPR = AMD*JNPR;
	AMD_MU = AMD*MU;
	AMD_PANW = AMD*PANW;
	ENPH_MU = ENPH*MU;
	ENPH_PANW = ENPH*PANW;
	ENPH_TEL = ENPH*TEL;
	MU_PANW = MU*PANW;
	MU_TEL = MU*TEL;
run;
/*testing quadratic terms */
proc reg data=stock2;
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL
	JNPRSQ MUSQ ENPHSQ;
	run;
/*remove insignifigant terms*/
proc reg data=stock2;
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL
	JNPRSQ MUSQ;
	run;
/*quad model */
proc reg data=stock2;
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL
	JNPRSQ;
	run;
/*testin potential interatction terms */
proc reg data=stock2;
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL
	AKAM_ENPH AKAM_JNPR AKAM_PANW
	AMD_ENPH AMD_JNPR AMD_MU AMD_PANW
	ENPH_MU ENPH_PANW ENPH_TEL
	MU_PANW MU_TEL;
	run;
/*remove insignifignat terms */
proc reg data=stock2; 	
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL 	
	AMD_ENPH AMD_JNPR ENPH_TEL; 	
	run;
/*remove insignifignat terms */
proc reg data=stock2; 	
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL 	
	AMD_ENPH AMD_JNPR; 	
	run;
/*best interaction model */
proc reg data=stock2; 	
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL 	
	AMD_JNPR; 	
	run;
/*model with interaction and one quad term*/
proc reg data=stock2; 	
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL 	
	AMD_JNPR JNPRSQ; 	
	run;

/*/all*/
/*first order model */
proc reg data=stock;
	model NTAP=AKAM AMD ENPH JNPR 
	MU PANW TEL/all;
	run;
/*quad model */
proc reg data=stock2;
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL
	JNPRSQ/all;
	run;
/*best interaction model */
proc reg data=stock2; 	
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL 	
	AMD_JNPR/all; 	
	run;
/*model with interaction and one quad term*/
proc reg data=stock2; 	
	model NTAP=AKAM AMD ENPH JNPR MU PANW TEL 	
	AMD_JNPR JNPRSQ/all; 	
	run;
	
