<template>
    <div class="container-fluid">

        <!--Start Dashboard Content-->

        <div class="card mt-3">
            <div class="card-content">
                <div class="row row-group m-0">
                    <div class="col-12 col-lg-6 col-xl-3 border-light">
                        <div class="card-body">
                            <h5 class="text-white mb-0">9526 <span class="float-right"><i
                                        class="fa fa-shopping-cart"></i></span>
                            </h5>
                            <div class="progress my-3" style="height:3px;">
                                <div class="progress-bar" style="width:55%"></div>
                            </div>
                            <p class="mb-0 text-white small-font">Total Orders <span class="float-right">+4.2% <i
                                        class="zmdi zmdi-long-arrow-up"></i></span></p>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6 col-xl-3 border-light">
                        <div class="card-body">
                            <h5 class="text-white mb-0">8323 <span class="float-right"><i class="fa fa-usd"></i></span></h5>
                            <div class="progress my-3" style="height:3px;">
                                <div class="progress-bar" style="width:55%"></div>
                            </div>
                            <p class="mb-0 text-white small-font">Total Revenue <span class="float-right">+1.2% <i
                                        class="zmdi zmdi-long-arrow-up"></i></span></p>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6 col-xl-3 border-light">
                        <div class="card-body">
                            <h5 class="text-white mb-0">6200 <span class="float-right"><i class="fa fa-eye"></i></span></h5>
                            <div class="progress my-3" style="height:3px;">
                                <div class="progress-bar" style="width:55%"></div>
                            </div>
                            <p class="mb-0 text-white small-font">Visitors <span class="float-right">+5.2% <i
                                        class="zmdi zmdi-long-arrow-up"></i></span></p>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6 col-xl-3 border-light">
                        <div class="card-body">
                            <h5 class="text-white mb-0">5630 <span class="float-right"><i class="fa fa-envira"></i></span>
                            </h5>
                            <div class="progress my-3" style="height:3px;">
                                <div class="progress-bar" style="width:55%"></div>
                            </div>
                            <p class="mb-0 text-white small-font">Messages <span class="float-right">+2.2% <i
                                        class="zmdi zmdi-long-arrow-up"></i></span></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="row">
            <div class="col-12 col-lg-8 col-xl-8">
                <div class="card">
                    <div class="card-header">Site Traffic
                        <div class="card-action">
                            <div class="dropdown">
                                <a href="javascript:void();" class="dropdown-toggle dropdown-toggle-nocaret"
                                    data-toggle="dropdown">
                                    <i class="icon-options"></i>
                                </a>
                                <div class="dropdown-menu dropdown-menu-right">
                                    <a class="dropdown-item" href="javascript:void();">Action</a>
                                    <a class="dropdown-item" href="javascript:void();">Another action</a>
                                    <a class="dropdown-item" href="javascript:void();">Something else here</a>
                                    <div class="dropdown-divider"></div>
                                    <a class="dropdown-item" href="javascript:void();">Separated link</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card-body">
                        <ul class="list-inline">
                            <li class="list-inline-item"><i class="fa fa-circle mr-2 text-white"></i>New Visitor</li>
                            <li class="list-inline-item"><i class="fa fa-circle mr-2 text-light"></i>Old Visitor</li>
                        </ul>
                        <div class="chart-container-1">
                            <canvas id="chart1"></canvas>
                        </div>
                    </div>

                    <div class="row m-0 row-group text-center border-top border-light-3">
                        <div class="col-12 col-lg-4">
                            <div class="p-3">
                                <h5 class="mb-0">45.87M</h5>
                                <small class="mb-0">Overall Visitor <span> <i class="fa fa-arrow-up"></i>
                                        2.43%</span></small>
                            </div>
                        </div>
                        <div class="col-12 col-lg-4">
                            <div class="p-3">
                                <h5 class="mb-0">15:48</h5>
                                <small class="mb-0">Visitor Duration <span> <i class="fa fa-arrow-up"></i>
                                        12.65%</span></small>
                            </div>
                        </div>
                        <div class="col-12 col-lg-4">
                            <div class="p-3">
                                <h5 class="mb-0">245.65</h5>
                                <small class="mb-0">Pages/Visit <span> <i class="fa fa-arrow-up"></i> 5.62%</span></small>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

            <div class="col-12 col-lg-4 col-xl-4">
                <div class="card">
                    <div class="card-header">Weekly sales
                        <div class="card-action">
                            <div class="dropdown">
                                <a href="javascript:void();" class="dropdown-toggle dropdown-toggle-nocaret"
                                    data-toggle="dropdown">
                                    <i class="icon-options"></i>
                                </a>
                                <div class="dropdown-menu dropdown-menu-right">
                                    <a class="dropdown-item" href="javascript:void();">Action</a>
                                    <a class="dropdown-item" href="javascript:void();">Another action</a>
                                    <a class="dropdown-item" href="javascript:void();">Something else here</a>
                                    <div class="dropdown-divider"></div>
                                    <a class="dropdown-item" href="javascript:void();">Separated link</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card-body">
                        <div class="chart-container-2">
                            <canvas id="chart2"></canvas>
                        </div>
                    </div>
                    <div class="table-responsive">
                        <table class="table align-items-center">
                            <tbody>
                                <tr>
                                    <td><i class="fa fa-circle text-white mr-2"></i> Direct</td>
                                    <td>$5856</td>
                                    <td>+55%</td>
                                </tr>
                                <tr>
                                    <td><i class="fa fa-circle text-light-1 mr-2"></i>Affiliate</td>
                                    <td>$2602</td>
                                    <td>+25%</td>
                                </tr>
                                <tr>
                                    <td><i class="fa fa-circle text-light-2 mr-2"></i>E-mail</td>
                                    <td>$1802</td>
                                    <td>+15%</td>
                                </tr>
                                <tr>
                                    <td><i class="fa fa-circle text-light-3 mr-2"></i>Other</td>
                                    <td>$1105</td>
                                    <td>+5%</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
        <!--End Row-->

        <div class="row">
            <div class="col-12 col-lg-6 col-xl-4">
                <div class="card">
                    <div class="card-body">
                        <div class="media align-items-center">
                            <div class="w_chart easy-dash-chart" data-percent="60">
                                <span class="w_percent"></span>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="mb-0">Facebook Followers</h6>
                                <small class="mb-0">22.14% <i class="fa fa-arrow-up"></i> Since Last Week</small>
                            </div>
                            <i class="fa fa-facebook text-white text-right fa-2x"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-lg-6 col-xl-4">
                <div class="card">
                    <div class="card-body">
                        <div class="media align-items-center">
                            <div class="w_chart easy-dash-chart" data-percent="65">
                                <span class="w_percent"></span>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="mb-0">Twitter Tweets</h6>
                                <small class="mb-0">32.15% <i class="fa fa-arrow-up"></i> Since Last Week</small>
                            </div>
                            <i class="fa fa-twitter text-white text-right fa-2x"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-lg-12 col-xl-4">
                <div class="card">
                    <div class="card-body">
                        <div class="media align-items-center">
                            <div class="w_chart easy-dash-chart" data-percent="75">
                                <span class="w_percent"></span>
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="mb-0">Youtube Subscribers</h6>
                                <small class="mb-0">58.24% <i class="fa fa-arrow-up"></i> Since Last Week</small>
                            </div>
                            <i class="fa fa-youtube text-white fa-2x"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!--End Row-->


        <div class="row">
            <div class="col-12 col-lg-12 col-xl-6">
                <div class="card">
                    <div class="card-header">World Selling Region
                        <div class="card-action">
                            <div class="dropdown">
                                <a href="javascript:void();" class="dropdown-toggle dropdown-toggle-nocaret"
                                    data-toggle="dropdown">
                                    <i class="icon-options"></i>
                                </a>
                                <div class="dropdown-menu dropdown-menu-right">
                                    <a class="dropdown-item" href="javascript:void();">Action</a>
                                    <a class="dropdown-item" href="javascript:void();">Another action</a>
                                    <a class="dropdown-item" href="javascript:void();">Something else here</a>
                                    <div class="dropdown-divider"></div>
                                    <a class="dropdown-item" href="javascript:void();">Separated link</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="card-body">
                        <div id="dashboard-map" style="height: 275px;"></div>
                    </div>
                    <div class="table-responsive">
                        <table class="table table-hover align-items-center">
                            <thead>
                                <tr>
                                    <th>Country</th>
                                    <th>Income</th>
                                    <th>Trend</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td><i class="flag-icon flag-icon-ca mr-2"></i> USA</td>
                                    <td>4,586$</td>
                                    <td><span id="trendchart1"></span></td>
                                </tr>
                                <tr>
                                    <td><i class="flag-icon flag-icon-us mr-2"></i>Canada</td>
                                    <td>2,089$</td>
                                    <td><span id="trendchart2"></span></td>
                                </tr>

                                <tr>
                                    <td><i class="flag-icon flag-icon-in mr-2"></i>India</td>
                                    <td>3,039$</td>
                                    <td><span id="trendchart3"></span></td>
                                </tr>

                                <tr>
                                    <td><i class="flag-icon flag-icon-gb mr-2"></i>UK</td>
                                    <td>2,309$</td>
                                    <td><span id="trendchart4"></span></td>
                                </tr>

                                <tr>
                                    <td><i class="flag-icon flag-icon-de mr-2"></i>Germany</td>
                                    <td>7,209$</td>
                                    <td><span id="trendchart5"></span></td>
                                </tr>

                            </tbody>
                        </table>
                    </div>
                </div>
            </div>

            <div class="col-12 col-lg-12 col-xl-6">
                <div class="row">
                    <div class="col-12 col-lg-6">
                        <div class="card">
                            <div class="card-body">
                                <p>Page Views</p>
                                <h4 class="mb-0">8,293 <small class="small-font">5.2% <i
                                            class="zmdi zmdi-long-arrow-up"></i></small></h4>
                            </div>
                            <div class="chart-container-3">
                                <canvas id="chart3"></canvas>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="card">
                            <div class="card-body">
                                <p>Total Clicks</p>
                                <h4 class="mb-0">7,493 <small class="small-font">1.4% <i
                                            class="zmdi zmdi-long-arrow-up"></i></small></h4>
                            </div>
                            <div class="chart-container-3">
                                <canvas id="chart4"></canvas>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="card">
                            <div class="card-body text-center">
                                <p class="mb-4">Total Downloads</p>
                                <input class="knob" data-width="175" data-height="175" data-readOnly="true"
                                    data-thickness=".2" data-angleoffset="90" data-linecap="round"
                                    data-bgcolor="rgba(255, 255, 255, 0.14)" data-fgcolor="#fff" data-max="15000"
                                    value="8550" />
                                <hr>
                                <p class="mb-0 small-font text-center">3.4% <i class="zmdi zmdi-long-arrow-up"></i> since
                                    yesterday
                                </p>
                            </div>
                        </div>
                    </div>
                    <div class="col-12 col-lg-6">
                        <div class="card">
                            <div class="card-body">
                                <p>Device Storage</p>
                                <h4 class="mb-3">42620/50000</h4>
                                <hr>
                                <div class="progress-wrapper mb-4">
                                    <p>Documents <span class="float-right">12GB</span></p>
                                    <div class="progress" style="height:5px;">
                                        <div class="progress-bar" style="width:80%"></div>
                                    </div>
                                </div>

                                <div class="progress-wrapper mb-4">
                                    <p>Images <span class="float-right">10GB</span></p>
                                    <div class="progress" style="height:5px;">
                                        <div class="progress-bar" style="width:60%"></div>
                                    </div>
                                </div>

                                <div class="progress-wrapper mb-4">
                                    <p>Mails <span class="float-right">5GB</span></p>
                                    <div class="progress" style="height:5px;">
                                        <div class="progress-bar" style="width:40%"></div>
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
        <!--End Row-->


        <div class="row">
            <div class="col-12 col-lg-6 col-xl-4">
                <div class="card">
                    <div class="card-body">
                        <p>Total Earning</p>
                        <h4 class="mb-0">287,493$</h4>
                        <small>1.4% <i class="zmdi zmdi-long-arrow-up"></i> Since Last Month</small>
                        <hr>
                        <p>Total Sales</p>
                        <h4 class="mb-0">87,493</h4>
                        <small>5.43% <i class="zmdi zmdi-long-arrow-up"></i> Since Last Month</small>
                        <div class="mt-5">
                            <div class="chart-container-4">
                                <canvas id="chart5"></canvas>
                            </div>
                        </div>
                    </div>
                </div>

            </div>

           
        </div>
        <!--End Row-->

        <!--End Row-->

        <!--End Dashboard Content-->
        <!--start overlay-->
        <div class="overlay"></div>
        <!--end overlay-->

    </div>
    <!-- End container-fluid-->
    </template>

<script>
export default {

}
</script>

<style></style>
