# bindisp

Matlab program for bindisp file I/O. The scripts intend to help constructing binary bindisp files or read them in Matlab enviroment.

The matlab data structrue which is used in this software is listed as below:

* struct    
 *             .name       [char*8] 8 letter station ID, fill in with space if less <\tab>
 *             .coord      [x y z] Cartisian coordinates in meter
 *             .dtime      [scale] time interval in second
 *             .t0         [date vector] [year month day hour minute second] begin time
 *             .tend       [date vector] [year month day hour minute second] end time
 *             .xyzr       [n*4] [dx dy dz zeros] the last column is preserved as zeros


% Author:       Lin Wang @ Frankfurt a.M.
% Written at:   2019-01-28  16:55 UTC
