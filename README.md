#  Design a Wind Energy System to Power a House

![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/0700892d-3052-4803-950a-f86ab540ecdc)
![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/39fa714e-52a6-40cc-9741-cddf1ea34fed)



## SOFTWARE REQUIREMENTS


- HOMER PRO

## ABOUT THE PROJECT

```
The project objective is to design an off-grid wind turbine system having an autonomy of
3-days using battery storage to provide a reliable and sustainable source of electric power.
Homer Pro software is used to get the wind speed data for any Longitude and latitude using
NASA average wind speed Models and annual load profile is updated in the software. Then
converters, batteries and wind turbines are selected based on the wind profile, autonomy
and peak load requirements. The wind turbine is selected such that it operates at max output
even in the months of low wind speed based on the power vs wind speed curve. Then, cable
specification and wiring diagrams required for the wind turbine are calculated and
illustrated respectively.

 
```
## Getting Started
## Specifications and layout of the House
1) Determine the longitude and latitude of the location. Then, determine the dimensions of the house
   and the frequency and voltage provided by the power utility company.
2) Determine the total load in the house and from that, calculate the kwh/day consumption.
   


## Battery Specification and Sizing
1) Calculate the corrected load:
   ![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/5f96b0f6-d5f3-4dc0-a810-02c8a44ac256)

2) After calculating corrected load, determine battery capacity:
   ![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/ac8d2254-4042-444b-ad88-7203e4c80e93)

3) Then select the appropriate batteries from  the Homer Pro and calculate the No of batteries Required:
   ![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/1d2b73b3-8d13-420e-99b3-d6566e78fdb5)
## Converter Specification
1) Determine the inverter size by taking into account Safety factor and choose the suitable model as per your load:
   ![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/62ea44e8-08b8-4874-99b1-2a1c0ee4f05d)


## Wind Turbine Specification
1) Firstly, the longitude and latitude of selected location is fed into
the HOMER PRO software and monthly average wind speed at 50m above the surface of the earth
over a 30 year period (Jan 1984-Dec 2013) is downloaded from the NASA Prediction of
Worldwide Energy Resource (Power) database.
![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/5d1750ca-3359-4a78-b5f8-4f4e560d940c)

 2) Based on the average wind speed, select the suitable wind turbine by looking at the power curve of different wind turbines inside the Homer Pro.
     Below is an example where EO10 is selcted based on the average wind speed.
![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/4db1e71f-d02d-4ae5-b6a5-7a225ebb65c5)

## Cable Specifications

1) Determine the load current and calulate the resisteance to compensate for temperature.
   Also make sure the voltage drop is within acceptable range as per NEC specifications:
 ![image](https://github.com/zainalibhinder/Design-a-Wind-Energy-System-to-power-a-House/assets/109630795/19d049d7-ca36-4af1-9360-5ac280c55df9)
Rest of the caluculation is given in the project report.






## License
&copy; 
[ZAIN ALI BHINDER](https://github.com/ZAINALIBHINDER)
