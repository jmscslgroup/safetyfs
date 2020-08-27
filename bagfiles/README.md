
# Description of bagfiles

## `fs-test1_dxmin_4.5_dx_activate_6.0_2020-08-26-15-51-51.bag`

Ran with fs-test1.launch - when followerstopper is made to follower leader with exact leader velocity as if followerstopper knowns what is the leader's velocity.

## `fs-test1_dxmin_4.5_dx_activate_6.0_2020-08-26-16-12-13.bag`

Ran with fs-test1.launch - when followerstopper is made to follower leader with exact leader velocity as if followerstopper knowns what is the leader's velocity is estimated by `v_lead = v_ego + v_relative`

## `fs-test1_dxmin_4.5_dx_activate_6.0_2020-08-26-16-51-44.bag` 

Same as the second one, but first relative distance is filtered using Kalman filter from kf.slx model and then `v_relative` is estimated.

