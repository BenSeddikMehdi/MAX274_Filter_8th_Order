# MAX274 2nd, 4th, 6th and 8th Order Filters.

The MAX274 is continuous-time active filter consisting of independent cascadable 2nd-Order sections.

 It comprises four 2nd-order section.


I have worked on the implementation of BandPass and LowPass filters of several orders 2nd, 4th, 6th and 8th.

Firstly, I started with reading the Datasheet of MAX274 to understand how things work. To achieve the goal of building a filter with a Bandwidth = [18Khz, 22Khz] and a maximum Gain at this Bandwidth, we need to calculate first the external values of the components and choose the best fit of the center frequency and quality factor and collect them.

Once we done with 2nd-Order filter we duplicate it 3 times and connect them in Cascade Mode to obtain the filter of 8th-Order.
