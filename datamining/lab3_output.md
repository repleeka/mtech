Apriori

Parameter specification:
 confidence minval smax arem  aval originalSupport maxtime support minlen
        0.2    0.1    1 none FALSE            TRUE       5    0.01      1
 maxlen target  ext
     10  rules TRUE

Algorithmic control:
 filter tree heap memopt load sort verbose
    0.1 TRUE TRUE  FALSE TRUE    2    TRUE

Absolute minimum support count: 98 

set item appearances ...[0 item(s)] done [0.00s].
set transactions ...[169 item(s), 9835 transaction(s)] done [0.00s].
sorting and recoding items ... [88 item(s)] done [0.00s].
creating transaction tree ... done [0.00s].
checking subsets of size 1 2 3 4 done [0.00s].
writing ... [232 rule(s)] done [0.00s].
creating S4 object  ... done [0.00s].
     lhs                rhs                support    confidence coverage  
[1]  {}              => {whole milk}       0.25551601 0.2555160  1.00000000
[2]  {hard cheese}   => {whole milk}       0.01006609 0.4107884  0.02450432
[3]  {butter milk}   => {other vegetables} 0.01037112 0.3709091  0.02796136
[4]  {butter milk}   => {whole milk}       0.01159126 0.4145455  0.02796136
[5]  {ham}           => {whole milk}       0.01148958 0.4414062  0.02602949
[6]  {sliced cheese} => {whole milk}       0.01077783 0.4398340  0.02450432
[7]  {oil}           => {whole milk}       0.01128622 0.4021739  0.02806304
[8]  {onions}        => {other vegetables} 0.01423488 0.4590164  0.03101169
[9]  {onions}        => {whole milk}       0.01209964 0.3901639  0.03101169
[10] {berries}       => {yogurt}           0.01057448 0.3180428  0.03324860
     lift     count
[1]  1.000000 2513 
[2]  1.607682   99 
[3]  1.916916  102 
[4]  1.622385  114 
[5]  1.727509  113 
[6]  1.721356  106 
[7]  1.573968  111 
[8]  2.372268  140 
[9]  1.526965  119 
[10] 2.279848  104 
null device 
          1 
