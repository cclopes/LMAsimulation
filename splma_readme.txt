New Mexico Tech Lightning Mapping Array - analyzed data                 
Analysis program: /data2/SPLMA/bin/lma_analysis_10.8.3 -d 20111107 -t 180000 -s 3600 -l /data2/SPLMA/loc/sp -n 6 -o output -q -x 5.00 [datafiles]         
          
Analysis program version: 10.8.3                                        
Analysis started: Thu Jan 26 18:41:33 2012                              
Analysis finished: Thu Jan 26 18:46:40 2012                             
Data start time: 11 07 11 18:00:00
Number of seconds analyzed: 3600                                        
Location: SPLMA                                                         
Coordinate center (lat,lon,alt): -23.5489740 -46.6388100 0.00           
Number of stations: 12                                                  
Number of active stations: 10                                           
Active stations: A B C D E F G J K L                                    
Minimum number of stations per solution: 6                              
Maximum reduced chi-squared: 5.00                                       
Maximum number of chi-squared iterations: 20                            
Station information: id, name, lat(d), lon(d), alt(m), delay(ns), board_rev, rec_ch 
Sta_info: A  MKZ               -23.4877967  -46.8316478   808.80  833 3  8      
Sta_info: B  UAB               -23.7022186  -46.8251392   783.80  743 3  8      
Sta_info: C  PCT               -23.6507108  -46.6218817   825.30  711 3  8      
Sta_info: D  FEI               -23.7257086  -46.5795603   828.30  725 3  8      
Sta_info: E  IFP               -23.5615964  -46.7350819   805.60  726 3 10      
Sta_info: F  CSP               -23.5241736  -46.6218442   750.30  722 3  8      
Sta_info: G  RBP               -23.7078239  -46.4100264   823.40  744 3  8      
Sta_info: H  PQC               -46.4592950  -23.5766592   842.24  867 3  8      
Sta_info: J  ULE               -23.4818842  -46.5005947   760.90  731 3  8      
Sta_info: K  MGC               -23.5137581  -46.1556681   765.42  737 3  8      
Sta_info: L  CSZ               -23.5359581  -46.3274372   749.35  736 3  8      
Sta_info: M  ARJ               -23.3748692  -46.3502872   841.61  730 3  8      
Station data: id, name, win(us), dec_win(us), data_ver, rms_error(ns), sources, %, <P/P_m>, active 
Sta_data: A  MKZ                 80    80   8  70     1557  92.7  0.92   A      
Sta_data: B  UAB                 80    80   8  70     1093  65.1  0.16   A      
Sta_data: C  PCT                 80    80   8  70     1542  91.8  1.53   A      
Sta_data: D  FEI                 80    80   8  70     1302  77.5  1.12   A      
Sta_data: E  IFP                 80    80   8  70      541  32.2  0.60   A      
Sta_data: F  CSP                 80    80   8  70      599  35.7  3.44   A      
Sta_data: G  RBP                 80    80   8  70      870  51.8  0.55   A      
Sta_data: H  PQC                  0     0   0  70        0   0.0   0.0  NA      
Sta_data: J  ULE                 80    80   8  70     1569  93.4  1.37   A      
Sta_data: K  MGC                 80    80   8  70      448  26.7  0.57   A      
Sta_data: L  CSZ                 80    80   8  70     1077  64.1  0.91   A      
Sta_data: M  ARJ                  0     0   0  70        0   0.0   0.0  NA      
Metric file version: 2                                                  
Initial metric: lowest of (c*delta_t * (1 + rchi2^2/4.0))               
Stop-early combination search: 5 metric repeats                         
Final metric: lowest of initial_metric * fuzzy_factor * max (1, rchi2/1.
Minimum forego ratio (unique/total combinations): 0.699                 
Fuzzy table factors: log base 2                                         
Fuzzy table: repeats(rows) 1 to 7, num_stations(cols) 4 to 12           
Fuzzy_data:   15.0    7.5    0.0   -7.5  -15.0  -22.5  -30.0  -37.5  -45.0      
Fuzzy_data:   14.0    6.5   -1.0   -8.5  -16.0  -23.5  -31.0  -38.5  -46.0      
Fuzzy_data:   13.0    5.5   -2.0   -9.5  -17.0  -24.5  -32.0  -39.5  -47.0      
Fuzzy_data:   12.0    4.5   -3.0  -10.5  -18.0  -25.5  -33.0  -40.5  -48.0      
Fuzzy_data:   11.0    3.5   -4.0  -11.5  -19.0  -26.5  -34.0  -41.5  -49.0      
Fuzzy_data:   10.0    2.5   -5.0  -12.5  -20.0  -27.5  -35.0  -42.5  -50.0      
Fuzzy_data:    9.0    1.5   -6.0  -13.5  -21.0  -28.5  -36.0  -43.5  -51.0      
Discarded solutions (stations,repeats):                                 
Station mask order: MLKJHGFEDCBA                                        
Data: time (UT sec of day), lat, lon, alt(m), reduced chi^2, P(dBW), mask, range,nstations, flash_num, Nsource
Data format: f15.9,1x,f10.6,1x,f11.6,1x,f7.1,1x,f5.2,1x,f5.1,1x,a4,1x,f10.4,1x,i3,1x,i6,1x,i1
Number of events:        1121
 ***data***
64802.840258417 -23.683315  -46.462669 22627.8  1.47   3.7 0276    23.3343   6      1 0001
64821.055443261 -22.912296  -46.580750 12501.6  0.71  16.8 054e    70.7602   6      2 0001
64827.924712721 -22.566666  -47.528782 15510.5  2.01  16.4 0547   141.9577   6      3 0001
64837.471985138 -22.645676  -46.368622 10220.7  0.33  16.8 051d   103.7949   6      4 0002
