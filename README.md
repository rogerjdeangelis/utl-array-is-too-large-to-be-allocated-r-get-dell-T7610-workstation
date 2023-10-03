# utl-array-is-too-large-to-be-allocated-r-get-dell-T7610-workstation
Array is too large to be allocated r get dell T7610 workstation
    %let pgm=utl-array-is-too-large-to-be-allocated-r-get-dell-T7610-workstation;

    Array is too large to be allocated r get dell T7610 workstation;
    Note T7610 does not support multichannel NVMe drives, you need an adapter card.

    Go to ebay look for a system like the T7610 with 128gb ram.
    I paid $600 for mine a few years ago. Probably much less now.
    I have no association with Dell.

    Your array is less than 37gb.

    github
    https://tinyurl.com/bd47puy2
    https://github.com/rogerjdeangelis/utl-array-is-too-large-to-be-allocated-r-get-dell-T7610-workstation


    https://tinyurl.com/3ua3kz9c
    https://stackoverflow.com/questions/77215030/my-array-is-too-large-to-be-allocated-what-can-i-do-to-split-it-into-smaller-ch

    Problem

      Sum all cells in the four dimensional array(583,712,30,365) with 1 in every cell

         my_data_array <- array(1.,c(583, 712, 30, 365));  ==> loads 1 in each cell
         sum(my_data_array);                               ==> grand totyal all cells

    /*
     _ __  _ __ ___   ___ ___  ___ ___
    | `_ \| `__/ _ \ / __/ _ \/ __/ __|
    | |_) | | | (_) | (_|  __/\__ \__ \
    | .__/|_|  \___/ \___\___||___/___/
    |_|
    */

    %utl_submit_wps64x("
    proc r;
    submit;
    lons <- 583;
    lats <- 712;
    my_data_array <- array(1.,c(lons, lats, 30, 365));
    sum(my_data_array);
    583*712*30*365;
    endsubmit;
    ");

    /*----                                                                   ----*/
    /*----  Takes less than 30 seconds                                       ----*/
    /*----                                                                   ----*/

    /*           _               _
      ___  _   _| |_ _ __  _   _| |_
     / _ \| | | | __| `_ \| | | | __|
    | (_) | |_| | |_| |_) | |_| | |_
     \___/ \__,_|\__| .__/ \__,_|\__|
                    |_|
    */

    /**************************************************************************************************************************/
    /*                                                                                                                        */
    /* The WPS System                                                                                                         */
    /*                                                                                                                        */
    /* sum(my_data_array)  =  [1] 4545301200   1 in evey cell                                                                 */
    /* 583*712*30*365      =  [1] 4545301200   583*1 * 712*1 * 30 * 1 * 365 * 1                                               */
    /*                                                                                                                        */
    /**************************************************************************************************************************/

    /*              _
      ___ _ __   __| |
     / _ \ `_ \ / _` |
    |  __/ | | | (_| |
     \___|_| |_|\__,_|

    */
