# SDS-modelling
**Broken sizes** - sizes with incorrect target value (incorrect from business logic);

**Correct sizes** - sizes with nice behaviour of t.v.;

**Model** - .ipynb file contains following scripts: `reader`, `converter`, `writer`, `documentation`, `OHE module`, `graphs` (for raw and predicted data), `linear regression model`;

**Report** - .ipynb file with some summaries of project;

*About sizes:* There is a pattern to which all measurement .txt/.md files are aligned - 
```
protection=<protecrion_value>
HW_chassis=<hardware_chassis_value>

### <number_of_nodes> nodes <object's_size> <type> // begin of size
INFO[<time>] Load started at: <date> (<timezone>) source=<source_value> 
INFO[<time>] Load finished at: <date> (<timezone>)source=<source_value>   
█ setup

\``` // begin of block with size results from one installation
 █ teardown

 aws_obj_put_bytes......: <float> <unit_of_measurement>  <float><unit_of_measurement>/s
 aws_obj_put_duration...: avg=<float><unit_of_measurement> min=<float><unit_of_measurement> med=<float><unit_of_measurement> max=<float><unit_of_measurement> p(90)=<float><unit_of_measurement>  p(95)=<float><unit_of_measurement>
 aws_obj_put_success....: <float> <float>/s
 data_received..........: <float> <unit_of_measurement> <float> <unit_of_measurement>/s
 data_sent..............: <float> <unit_of_measurement> <float> <unit_of_measurement>/s
 iteration_duration.....: avg=<float><unit_of_measurement> min=<float><unit_of_measurement> med=<float><unit_of_measurement> max=<float><unit_of_measurement> p(90)=<float><unit_of_measurement>  p(95)=<float><unit_of_measurement>
 iterations.............: <float> <float>/s
 vus....................: <float> min=<float> max=<float>
\``` // end of block with size results from one installation
// there can be several blocks for one size
```
