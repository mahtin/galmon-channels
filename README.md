# galmon-channels
A quick script to show which received GNSS channels/frequencies a [galmon](https://github.com/berthubert/galmon) installation is receiving.

It assumed the standard galmon install (i.e log files in `/run/ubxtool/`).

## The script
It's at [galmon-channels.sh](galmon-channels.sh)

Don't forget to `chmod +x` the file once you've downloaded it.

## Results (for a U-Blox Series-9 ZED-F9P chip)
```
GPS:
		   L0	   L1	   L2	   L4	   L5	
	G01	G01@0	-----	-----	-----	-----	
	G02	G02@0	-----	-----	-----	-----	
	G05	G05@0	-----	-----	G05@4	-----	
	G06	G06@0	-----	-----	G06@4	-----	
	G07	G07@0	-----	-----	G07@4	-----	
	G08	G08@0	-----	-----	G08@4	-----	
	G10	G10@0	-----	-----	G10@4	-----	
	G11	G11@0	-----	-----	G11@4	-----	
	G12	G12@0	-----	-----	G12@4	-----	
	G13	G13@0	-----	-----	-----	-----	
	G14	G14@0	-----	-----	G14@4	-----	
	G15	G15@0	-----	-----	G15@4	-----	
	G16	G16@0	-----	-----	-----	-----	
	G17	G17@0	-----	-----	G17@4	-----	
	G18	G18@0	-----	-----	G18@4	-----	
	G19	G19@0	-----	-----	-----	-----	
	G20	G20@0	-----	-----	-----	-----	
	G21	G21@0	-----	-----	-----	-----	
	G22	G22@0	-----	-----	-----	-----	
	G23	G23@0	-----	-----	G23@4	-----	
	G24	G24@0	-----	-----	G24@4	-----	
	G25	G25@0	-----	-----	G25@4	-----	
	G26	G26@0	-----	-----	G26@4	-----	
	G27	G27@0	-----	-----	G27@4	-----	
	G28	G28@0	-----	-----	G28@4	-----	
	G29	G29@0	-----	-----	G29@4	-----	
	G30	G30@0	-----	-----	G30@4	-----	
	G31	G31@0	-----	-----	G31@4	-----	
	G32	G32@0	-----	-----	G32@4	-----	

SBAS:
		   L0	   L1	   L2	   L4	   L5	

Galileo:
		   L0	   L1	   L2	   L4	   L5	
	E02	-----	E02@1	-----	-----	E02@5	
	E03	-----	E03@1	-----	-----	E03@5	
	E05	-----	E05@1	-----	-----	E05@5	
	E07	-----	E07@1	-----	-----	E07@5	
	E08	-----	E08@1	-----	-----	E08@5	
	E10	-----	E10@1	-----	-----	E10@5	
	E11	-----	E11@1	-----	-----	E11@5	
	E12	-----	E12@1	-----	-----	E12@5	
	E13	-----	E13@1	-----	-----	E13@5	
	E14	-----	E14@1	-----	-----	E14@5	
	E15	-----	E15@1	-----	-----	E15@5	
	E18	-----	E18@1	-----	-----	E18@5	
	E21	-----	E21@1	-----	-----	E21@5	
	E24	-----	E24@1	-----	-----	E24@5	
	E25	-----	E25@1	-----	-----	E25@5	
	E26	-----	E26@1	-----	-----	E26@5	
	E27	-----	E27@1	-----	-----	E27@5	
	E30	-----	E30@1	-----	-----	E30@5	
	E33	-----	E33@1	-----	-----	E33@5	
	E34	-----	E34@1	-----	-----	E34@5	
	E36	-----	E36@1	-----	-----	E36@5	

BeiDou:
		   L0	   L1	   L2	   L4	   L5	
	B11	B11@0	-----	B11@2	-----	-----	
	B12	B12@0	-----	B12@2	-----	-----	
	B14	B14@0	-----	B14@2	-----	-----	
	B16	B16@0	-----	B16@2	-----	-----	
	B21	B21@0	-----	-----	-----	-----	
	B22	B22@0	-----	-----	-----	-----	
	B23	B23@0	-----	-----	-----	-----	
	B24	B24@0	-----	-----	-----	-----	
	B25	B25@0	-----	-----	-----	-----	
	B26	B26@0	-----	-----	-----	-----	
	B27	B27@0	-----	-----	-----	-----	
	B28	B28@0	-----	-----	-----	-----	
	B29	B29@0	-----	-----	-----	-----	
	B30	B30@0	-----	-----	-----	-----	
	B32	B32@0	-----	-----	-----	-----	
	B33	B33@0	-----	-----	-----	-----	
	B34	B34@0	-----	-----	-----	-----	
	B35	B35@0	-----	-----	-----	-----	
	B36	B36@0	-----	-----	-----	-----	
	B37	B37@0	-----	-----	-----	-----	

IMES:
		   L0	   L1	   L2	   L4	   L5	

QZSS:
		   L0	   L1	   L2	   L4	   L5	
	Q02	Q02@0	-----	-----	Q02@4	-----	

GLONASS:
		   L0	   L1	   L2	   L4	   L5	
	R01	R01@0	-----	R01@2	-----	-----	
	R02	R02@0	-----	R02@2	-----	-----	
	R04	R04@0	-----	R04@2	-----	-----	
	R05	R05@0	-----	R05@2	-----	-----	
	R06	R06@0	-----	-----	-----	-----	
	R07	R07@0	-----	R07@2	-----	-----	
	R08	R08@0	-----	R08@2	-----	-----	
	R09	R09@0	-----	R09@2	-----	-----	
	R10	R10@0	-----	-----	-----	-----	
	R11	R11@0	-----	R11@2	-----	-----	
	R12	R12@0	-----	R12@2	-----	-----	
	R13	R13@0	-----	R13@2	-----	-----	
	R14	R14@0	-----	R14@2	-----	-----	
	R15	R15@0	-----	R15@2	-----	-----	
	R16	R16@0	-----	R16@2	-----	-----	
	R17	R17@0	-----	R17@2	-----	-----	
	R18	R18@0	-----	R18@2	-----	-----	
	R19	R19@0	-----	R19@2	-----	-----	
	R20	R20@0	-----	R20@2	-----	-----	
	R21	R21@0	-----	R21@2	-----	-----	
	R22	R22@0	-----	R22@2	-----	-----	
	R23	R23@0	-----	-----	-----	-----	
	R24	R24@0	-----	R24@2	-----	-----	

NavIC:
		   L0	   L1	   L2	   L4	   L5	
```
## Results (for a U-Blox Series 8 chip)
```
GPS:
		   L0	   L1	
	G01	G01@0	-----	
	G02	G02@0	-----	
	G03	G03@0	-----	
	G04	G04@0	-----	
	G05	G05@0	-----	
	G06	G06@0	-----	
	G07	G07@0	-----	
	G08	G08@0	-----	
	G09	G09@0	-----	
	G10	G10@0	-----	
	G11	G11@0	-----	
	G12	G12@0	-----	
	G13	G13@0	-----	
	G14	G14@0	-----	
	G15	G15@0	-----	
	G16	G16@0	-----	
	G17	G17@0	-----	
	G18	G18@0	-----	
	G19	G19@0	-----	
	G20	G20@0	-----	
	G21	G21@0	-----	
	G22	G22@0	-----	
	G23	G23@0	-----	
	G24	G24@0	-----	
	G25	G25@0	-----	
	G26	G26@0	-----	
	G27	G27@0	-----	
	G28	G28@0	-----	
	G29	G29@0	-----	
	G30	G30@0	-----	
	G31	G31@0	-----	
	G32	G32@0	-----	

SBAS:
		   L0	   L1	

Galileo:
		   L0	   L1	
	E02	-----	E02@1	
	E03	-----	E03@1	
	E04	-----	E04@1	
	E05	-----	E05@1	
	E07	-----	E07@1	
	E08	-----	E08@1	
	E09	-----	E09@1	
	E10	-----	E10@1	
	E11	-----	E11@1	
	E12	-----	E12@1	
	E13	-----	E13@1	
	E14	-----	E14@1	
	E15	-----	E15@1	
	E18	-----	E18@1	
	E19	-----	E19@1	
	E20	-----	E20@1	
	E21	-----	E21@1	
	E24	-----	E24@1	
	E25	-----	E25@1	
	E26	-----	E26@1	
	E27	-----	E27@1	
	E30	-----	E30@1	
	E31	-----	E31@1	
	E33	-----	E33@1	
	E34	-----	E34@1	
	E36	-----	E36@1	

BeiDou:
		   L0	   L1	

IMES:
		   L0	   L1	

QZSS:
		   L0	   L1	

GLONASS:
		   L0	   L1	
	R01	R01@0	-----	
	R02	R02@0	-----	
	R03	R03@0	-----	
	R04	R04@0	-----	
	R05	R05@0	-----	
	R06	R06@0	-----	
	R07	R07@0	-----	
	R08	R08@0	-----	
	R09	R09@0	-----	
	R10	R10@0	-----	
	R11	R11@0	-----	
	R12	R12@0	-----	
	R13	R13@0	-----	
	R14	R14@0	-----	
	R15	R15@0	-----	
	R16	R16@0	-----	
	R17	R17@0	-----	
	R18	R18@0	-----	
	R19	R19@0	-----	
	R20	R20@0	-----	
	R21	R21@0	-----	
	R22	R22@0	-----	
	R23	R23@0	-----	
	R24	R24@0	-----	
	R255	R255@0	-----	

NavIC:
		   L0	   L1
```
     
