# Experimentation & Benchmarks: In progress 

### Training in OpenAI Gym + Resume
###### python 05_train_controller.py car_racing -n 8 -t 2 -e 4 --max_length=1000 --init_opt ./controller/car_racing.cma.4.16.es.pk |& tee ./controller/controller_train_2.log

## Bench_1: Start
#### CarRace Benchmark, DreamMode - car_racing.cma.4.16.best.json
######python model.py car_racing --filename ./controller/car_racing.cma.4.16.best.json --record_video --render --dream_mode --final_mode

episode 0 reward = 45.0
episode 1 reward = 48.0
episode 2 reward = 48.0
episode 3 reward = 51.0
episode 4 reward = 50.0
episode 5 reward = 51.0
episode 6 reward = 42.0
episode 7 reward = 44.0
episode 8 reward = 46.0
episode 9 reward = 48.0
episode 10 reward = 50.0
episode 11 reward = 62.0
episode 12 reward = 57.0
episode 13 reward = 52.0
episode 14 reward = 51.0
episode 15 reward = 56.0
episode 16 reward = 52.0
episode 17 reward = 47.0
episode 18 reward = 54.0
episode 19 reward = 52.0
episode 20 reward = 48.0
episode 21 reward = 51.0
episode 22 reward = 52.0
episode 23 reward = 55.0
episode 24 reward = 48.0
episode 25 reward = 46.0
episode 26 reward = 44.0
episode 27 reward = 47.0
episode 28 reward = 56.0
episode 29 reward = 45.0
episode 30 reward = 47.0
episode 31 reward = 51.0
episode 32 reward = 47.0
episode 33 reward = 56.0
episode 34 reward = 49.0
episode 35 reward = 49.0
episode 36 reward = 48.0
episode 37 reward = 46.0
episode 38 reward = 49.0
episode 39 reward = 52.0
episode 40 reward = 51.0
episode 41 reward = 53.0
episode 42 reward = 48.0
episode 43 reward = 52.0
episode 44 reward = 46.0
episode 45 reward = 45.0
episode 46 reward = 53.0
episode 47 reward = 41.0
episode 48 reward = 49.0
episode 49 reward = 49.0
episode 50 reward = 50.0
episode 51 reward = 50.0
episode 52 reward = 55.0
episode 53 reward = 61.0
episode 54 reward = 47.0
episode 55 reward = 63.0
episode 56 reward = 49.0
episode 57 reward = 49.0
episode 58 reward = 54.0
episode 59 reward = 56.0
episode 60 reward = 49.0
episode 61 reward = 47.0
episode 62 reward = 46.0
episode 63 reward = 48.0
episode 64 reward = 53.0
episode 65 reward = 46.0
episode 66 reward = 58.0
episode 67 reward = 50.0
episode 68 reward = 43.0
episode 69 reward = 51.0
episode 70 reward = 64.0
episode 71 reward = 65.0
episode 72 reward = 47.0
episode 73 reward = 46.0
episode 74 reward = 52.0
episode 75 reward = 66.0
episode 76 reward = 49.0
episode 77 reward = 48.0
episode 78 reward = 46.0
episode 79 reward = 47.0
episode 80 reward = 50.0
episode 81 reward = 43.0
episode 82 reward = 45.0
episode 83 reward = 59.0
episode 84 reward = 43.0
episode 85 reward = 49.0
episode 86 reward = 50.0
episode 87 reward = 65.0
episode 88 reward = 42.0
episode 89 reward = 46.0
episode 90 reward = 48.0
episode 91 reward = 52.0
episode 92 reward = 48.0
episode 93 reward = 47.0
episode 94 reward = 53.0
episode 95 reward = 45.0
episode 96 reward = 47.0
episode 97 reward = 55.0
episode 98 reward = 48.0
episode 99 reward = 50.0
seed 111 average_reward 50.19

# CarRace Benchmark, NoDreamMode - car_racing.cma.4.16.best.json
python model.py car_racing --filename ./controller/car_racing.cma.4.16.best.json --record_video --render --final_mode

episode 0 reward = 834.5454545454389
episode 1 reward = 620.5882352941084
episode 2 reward = 742.9487179487063
episode 3 reward = 510.34482758619276
episode 4 reward = 687.8787878787716
episode 5 reward = 635.015772870649
episode 6 reward = 844.6494464944548
episode 7 reward = 720.846905537445
episode 8 reward = 802.1739130434684
episode 9 reward = 838.2239382239211
episode 10 reward = 716.3934426229391
episode 11 reward = 115.82733812950147
episode 12 reward = 812.4579124578963
episode 13 reward = 631.3432835820778
episode 14 reward = 643.1506849314932
episode 15 reward = 674.41077441076
episode 16 reward = 731.615120274898
episode 17 reward = 783.802816901393
episode 18 reward = 751.4851485148425
episode 19 reward = 755.3054662379284
episode 20 reward = 718.1818181818082
episode 21 reward = 831.6546762589759
episode 22 reward = 756.1872909698842
episode 23 reward = 825.7950530035183
episode 24 reward = 871.9999999999858
episode 25 reward = 840.0749063670302
episode 26 reward = 827.2727272727118
episode 27 reward = 612.0253164556842
episode 28 reward = 856.521739130424
episode 29 reward = 563.0036630036508
episode 30 reward = 805.5944055943912
episode 31 reward = 799.6282527880913
episode 32 reward = 749.3150684931364
episode 33 reward = 867.0329670329553
episode 34 reward = 743.3333333333221
episode 35 reward = 669.23076923076
episode 36 reward = 485.8895705521364
episode 37 reward = 824.5283018867806
episode 38 reward = 264.261168384872
episode 39 reward = 417.68488745979363
episode 40 reward = 790.3225806451517
episode 41 reward = 875.3521126760384
episode 42 reward = 267.6975945017149
episode 43 reward = 315.8415841584045
episode 44 reward = 709.3645484949685
episode 45 reward = 829.6296296296143
episode 46 reward = 673.4627831715076
episode 47 reward = 836.567164179089
episode 48 reward = 850.5300353356741
episode 49 reward = 828.5714285714132
episode 50 reward = 854.0229885057371
episode 51 reward = 772.852233676961
episode 52 reward = 766.2420382165435
episode 53 reward = 878.4172661870333
episode 54 reward = 866.2921348314491
episode 55 reward = 861.9771863117693
episode 56 reward = 742.9118773946312
episode 57 reward = 809.3959731543465
episode 58 reward = 449.29577464787496
episode 59 reward = 885.507246376802
episode 60 reward = 371.3114754098205
episode 61 reward = 827.3356401383992
episode 62 reward = 838.1443298968911
episode 63 reward = 902.7999999999887
episode 64 reward = 531.9444444444324
episode 65 reward = 874.1697416974067
episode 66 reward = 610.2803738317615
episode 67 reward = 796.2962962962816
episode 68 reward = 691.0447761193918
episode 69 reward = 626.1538461538363
episode 70 reward = 874.1697416974066
episode 71 reward = 729.032258064507
episode 72 reward = 694.3925233644708
episode 73 reward = 789.2617449664277
episode 74 reward = 847.7351916376169
episode 75 reward = 716.4794007490515
episode 76 reward = 905.7999999999848
episode 77 reward = 786.7924528301766
episode 78 reward = 746.938775510195
episode 79 reward = 787.3239436619556
episode 80 reward = 819.2982456140197
episode 81 reward = 704.9535603715073
episode 82 reward = 880.8429118773855
episode 83 reward = 841.1764705882184
episode 84 reward = 881.617647058806
episode 85 reward = 528.1588447653291
episode 86 reward = 725.6578947368281
episode 87 reward = 659.8784194528782
episode 88 reward = 757.5949367088515
episode 89 reward = 654.3859649122654
episode 90 reward = 860.5734767024952
episode 91 reward = 888.9705882352765
episode 92 reward = 849.9999999999847
episode 93 reward = 634.0067340067187
episode 94 reward = 835.2517985611348
episode 95 reward = 550.6024096385424
episode 96 reward = 610.6109324758698
episode 97 reward = 901.8999999999899
episode 98 reward = 851.3108614232091
episode 99 reward = 559.9326599326522
seed 111 average_reward 729.9060939708544

## Bench_1: End

## Bench_2: Start
#### CarRace Benchmark, DreamMode - car_racing.cma.4.16.best.json150
######python model.py car_racing --filename ./controller/car_racing.cma.4.16.best.json150 --record_video --render --dream_mode --final_mode

episode 0 reward = 78.0
episode 1 reward = 76.0
episode 2 reward = 72.0
episode 3 reward = 77.0
episode 4 reward = 78.0
episode 5 reward = 79.0
episode 6 reward = 77.0
episode 7 reward = 79.0
episode 8 reward = 58.0
episode 9 reward = 79.0
episode 10 reward = 79.0
episode 11 reward = 79.0
episode 12 reward = 81.0
episode 13 reward = 79.0
episode 14 reward = 68.0
episode 15 reward = 68.0
episode 16 reward = 78.0
episode 17 reward = 77.0
episode 18 reward = 79.0
episode 19 reward = 77.0
episode 20 reward = 79.0
episode 21 reward = 78.0
episode 22 reward = 78.0
episode 23 reward = 78.0
episode 24 reward = 79.0
episode 25 reward = 78.0
episode 26 reward = 78.0
episode 27 reward = 77.0
episode 28 reward = 81.0
episode 29 reward = 80.0
episode 30 reward = 78.0
episode 31 reward = 80.0
episode 32 reward = 79.0
episode 33 reward = 80.0
episode 34 reward = 80.0
episode 35 reward = 77.0
episode 36 reward = 74.0
episode 37 reward = 81.0
episode 38 reward = 77.0
episode 39 reward = 79.0
episode 40 reward = 78.0
episode 41 reward = 76.0
episode 42 reward = 76.0
episode 43 reward = 80.0
episode 44 reward = 80.0
episode 45 reward = 78.0
episode 46 reward = 77.0
episode 47 reward = 78.0
episode 48 reward = 80.0
episode 49 reward = 80.0
episode 50 reward = 79.0
episode 51 reward = 77.0
episode 52 reward = 78.0
episode 53 reward = 84.0
episode 54 reward = 80.0
episode 55 reward = 79.0
episode 56 reward = 77.0
episode 57 reward = 80.0
episode 58 reward = 79.0
episode 59 reward = 79.0
episode 60 reward = 78.0
episode 61 reward = 77.0
episode 62 reward = 78.0
episode 63 reward = 78.0
episode 64 reward = 79.0
episode 65 reward = 80.0
episode 66 reward = 80.0
episode 67 reward = 78.0
episode 68 reward = 81.0
episode 69 reward = 79.0
episode 70 reward = 81.0
episode 71 reward = 79.0
episode 72 reward = 80.0
episode 73 reward = 78.0
episode 74 reward = 79.0
episode 75 reward = 79.0
episode 76 reward = 79.0
episode 77 reward = 81.0
episode 78 reward = 73.0
episode 79 reward = 82.0
episode 80 reward = 79.0
episode 81 reward = 78.0
episode 82 reward = 79.0
episode 83 reward = 76.0
episode 84 reward = 76.0
episode 85 reward = 76.0
episode 86 reward = 79.0
episode 87 reward = 75.0
episode 88 reward = 75.0
episode 89 reward = 79.0
episode 90 reward = 76.0
episode 91 reward = 81.0
episode 92 reward = 78.0
episode 93 reward = 76.0
episode 94 reward = 79.0
episode 95 reward = 80.0
episode 96 reward = 79.0
episode 97 reward = 73.0
episode 98 reward = 78.0
episode 99 reward = 77.0
seed 111 average_reward 77.92


#### CarRace Benchmark, NoDreamMode - car_racing.cma.4.16.best.json150
######python model.py car_racing --filename ./controller/car_racing.cma.4.16.best.json150 --record_video --render --final_mode

episode 0 reward = 863.6363636363462
episode 1 reward = 655.8823529411652
episode 2 reward = 707.6923076922972
episode 3 reward = 907.8999999999845
episode 4 reward = 442.424242424227
episode 5 reward = 808.5173501577152
episode 6 reward = 331.73431734315847
episode 7 reward = 844.6254071661041
episode 8 reward = 892.7536231883948
episode 9 reward = 853.6679536679353
episode 10 reward = 785.2459016393314
episode 11 reward = 324.4604316546787
episode 12 reward = 876.4309764309593
episode 13 reward = 335.8208955223752
episode 14 reward = 872.6027397260087
episode 15 reward = 842.7609427609264
episode 16 reward = 707.5601374570281
episode 17 reward = 889.4366197182912
episode 18 reward = 883.4983498349729
episode 19 reward = 861.4147909967693
episode 20 reward = 627.2727272727146
episode 21 reward = 403.59712230214257
episode 22 reward = 866.5551839464687
episode 23 reward = 645.5830388692513
episode 24 reward = 883.9999999999842
episode 25 reward = 836.3295880149691
episode 26 reward = 881.818181818164
episode 27 reward = 687.9746835442917
episode 28 reward = 809.0909090908974
episode 29 reward = 830.4029304029173
episode 30 reward = 651.748251748237
episode 31 reward = 814.4981412639254
episode 32 reward = 896.5753424657344
episode 33 reward = 911.0999999999906
episode 34 reward = 429.99999999998556
episode 35 reward = 616.923076923066
episode 36 reward = 614.723926380356
episode 37 reward = 877.3584905660255
episode 38 reward = 800.3436426116666
episode 39 reward = 768.1672025723324
episode 40 reward = 854.8387096774096
episode 41 reward = 829.5774647887139
episode 42 reward = 824.3986254295357
episode 43 reward = 843.8943894389337
episode 44 reward = 846.4882943143623
episode 45 reward = 877.7777777777605
episode 46 reward = 479.2880258899527
episode 47 reward = 455.97014925373065
episode 48 reward = 836.3957597172981
episode 49 reward = 864.2857142856965
episode 50 reward = 846.3601532566943
episode 51 reward = 882.8178694157893
episode 52 reward = 810.8280254776873
episode 53 reward = 901.6999999999825
episode 54 reward = 881.2734082396871
episode 55 reward = 877.1863117870523
episode 56 reward = 857.8544061302576
episode 57 reward = 876.5100671140757
episode 58 reward = 378.87323943660647
episode 59 reward = 909.5999999999905
episode 60 reward = 826.229508196703
episode 61 reward = 879.2387543252489
episode 62 reward = 879.3814432989512
episode 63 reward = 889.3617021276464
episode 64 reward = 667.3611111110949
episode 65 reward = 892.6199261992505
episode 66 reward = 778.5046728971778
episode 67 reward = 748.1481481481325
episode 68 reward = 789.5522388059553
episode 69 reward = 530.7692307692186
episode 70 reward = 892.6199261992502
episode 71 reward = 603.2258064516013
episode 72 reward = 787.8504672897017
episode 73 reward = 879.8657718120627
episode 74 reward = 879.0940766550372
episode 75 reward = 855.0561797752674
episode 76 reward = 873.4848484848311
episode 77 reward = 383.01886792451324
episode 78 reward = 886.3945578231192
episode 79 reward = 885.9154929577272
episode 80 reward = 840.3508771929654
episode 81 reward = 643.0340557275433
episode 82 reward = 888.5057471264262
episode 83 reward = 822.7941176470404
episode 84 reward = 863.2352941176281
episode 85 reward = 878.3393501804953
episode 86 reward = 370.3947368420907
episode 87 reward = 772.340425531903
episode 88 reward = 653.1645569620132
episode 89 reward = 847.3684210526134
episode 90 reward = 856.9892473118126
episode 91 reward = 877.9411764705695
episode 92 reward = 907.8999999999844
episode 93 reward = 418.51851851850415
episode 94 reward = 828.0575539568173
episode 95 reward = 454.2168674698673
episode 96 reward = 231.1897106109309
episode 97 reward = 865.6488549618198
episode 98 reward = 858.8014981273276
episode 99 reward = 859.5959595959429
seed 111 average_reward 760.241262358398


#### CarRace Benchmark, NoDreamMode - car_racing.cma.4.16.best.json125
######python model.py car_racing --filename ./controller/car_racing.cma.4.16.best.json125 --record_video --render --final_mode 

episode 0 reward = 834.5454545454379
episode 1 reward = 635.2941176470475
episode 2 reward = 807.0512820512685
episode 3 reward = 886.206896551707
episode 4 reward = 775.7575757575573
episode 5 reward = 701.2618296529821
episode 6 reward = 874.1697416974052
episode 7 reward = 222.47557003257168
episode 8 reward = 852.8985507246259
episode 9 reward = 502.3166023165853
episode 10 reward = 319.67213114752667
episode 11 reward = 813.6690647481845
episode 12 reward = 869.6969696969517
episode 13 reward = 317.91044776118224
episode 14 reward = 862.328767123269
episode 15 reward = 694.6127946127781
episode 16 reward = 848.4536082474049
episode 17 reward = 889.436619718291
episode 18 reward = 886.7986798679759
episode 19 reward = 465.9163987138114
episode 20 reward = 172.72727272727758
episode 21 reward = 842.44604316545
episode 22 reward = 796.3210702340955
episode 23 reward = 740.9893992932715
episode 24 reward = 871.9999999999852
episode 25 reward = 828.838951310849
episode 26 reward = 859.9999999999831
episode 27 reward = 855.6962025316352
episode 28 reward = 813.0434782608584
episode 29 reward = 475.09157509156057
episode 30 reward = 851.0489510489343
episode 31 reward = 803.3457249070491
episode 32 reward = 886.3013698629956
episode 33 reward = 912.7999999999901
episode 34 reward = 823.3333333333214
episode 35 reward = 619.9999999999883
episode 36 reward = 798.7730061349577
episode 37 reward = 862.2641509433831
episode 38 reward = 800.3436426116704
episode 39 reward = 549.5176848874453
episode 40 reward = 758.064516129021
episode 41 reward = 861.2676056337843
episode 42 reward = 796.9072164948283
episode 43 reward = 807.5907590758962
episode 44 reward = 813.0434782608514
episode 45 reward = 525.9259259259101
episode 46 reward = 728.478964401279
episode 47 reward = 862.6865671641618
episode 48 reward = 882.3321554770149
episode 49 reward = 900.4999999999826
episode 50 reward = 865.5172413792997
episode 51 reward = 886.2542955326285
episode 52 reward = 826.7515923566683
episode 53 reward = 907.6999999999833
episode 54 reward = 862.5468164793875
episode 55 reward = 858.1749049429457
episode 56 reward = 869.3486590038224
episode 57 reward = 908.7999999999838
episode 58 reward = 410.56338028167687
episode 59 reward = 852.8985507246258
episode 60 reward = 617.2131147540936
episode 61 reward = 889.6193771626193
episode 62 reward = 862.1993127147589
episode 63 reward = 871.6312056737463
episode 64 reward = 806.2499999999814
episode 65 reward = 874.1697416974051
episode 66 reward = 557.3208722741283
episode 67 reward = 707.407407407391
episode 68 reward = 595.5223880596888
episode 69 reward = 521.5384615384493
episode 70 reward = 888.9298892988812
episode 71 reward = 883.8709677419254
episode 72 reward = 697.5077881619776
episode 73 reward = 889.9328859060226
episode 74 reward = 840.7665505226337
episode 75 reward = 877.5280898876277
episode 76 reward = 888.6363636363474
episode 77 reward = 605.660377358486
episode 78 reward = 852.3809523809425
episode 79 reward = 811.9718309858979
episode 80 reward = 833.3333333333164
episode 81 reward = 664.7058823529292
episode 82 reward = 873.1800766283419
episode 83 reward = 848.5294117646865
episode 84 reward = 877.9411764705698
episode 85 reward = 914.2999999999939
episode 86 reward = 850.6578947368263
episode 87 reward = 781.458966565338
episode 88 reward = 428.48101265822714
episode 89 reward = 826.3157894736668
episode 90 reward = 867.7419354838557
episode 91 reward = 910.3999999999835
episode 92 reward = 807.1428571428397
episode 93 reward = 782.1548821548658
episode 94 reward = 842.4460431654505
episode 95 reward = 788.554216867457
episode 96 reward = 854.9839228295663
episode 97 reward = 880.9160305343387
episode 98 reward = 862.5468164793876
episode 99 reward = 873.0639730639551
seed 111 average_reward 773.1961938709156

#### Start retraining with 125th timestep as it has the average score of 773
######python 05_train_controller.py car_racing -n 6 -t 2 -e 4 --max_length=1000 --init_opt ./controller/train_2/car_racing.cma.4.16.es.pk125 |& tee ./controller/controller_train_4.log



#### Train-4: Start from scratch with 7 threads
######python 05_train_controller.py car_racing -n 6 -t 2 -e 4 --max_length=1000 |& tee ./controller/controller_train_4.log

#### Train-5: Continue training from pk95
python 05_train_controller.py car_racing -n 6 -t 2 -e 4 --max_length=1000 --init_opt ./controller/train4_n6/car_racing.cma.4.12.es.pk95 |& tee ./controller/train5_n6_cont95/controller_train_5.log

### Benchmark:
python model.py car_racing --filename ./controller/car_racing.cma.4.12.best.json125 --record_video --render --final_mode



### Train 6 - DreamMode:
xvfb-run -a -s "-screen 0 1400x900x24" python 05_train_controller.py car_racing -n 7 -t 2 -e 4 --max_length 1000 --dream_mode 1 |& tee ./controller/train7_dream/controller_train.log

### Train 7 - DreamMode: cont. (Generations 550 -> 'best' -25)
xvfb-run -a -s "-screen 0 1400x900x24" python 05_train_controller.py car_racing -n 7 -t 2 -e 4 --max_length 1000 --init_opt ./controller/train6_dream\(new\)/car_racing.cma.4.14.es.pk281 --dream_mode 1 |& tee ./controller/controller_train.log

python model.py car_racing --filename ./controller/car_racing.cma.4.14.best.json550 --render --record_video
# The result is still disappointing. Maybe the dream env. is the culprit here, too much randomization.


python model.py car_racing --filename ./controller/car_racing.cma.4.14.best.json275 --render --dream_mode
