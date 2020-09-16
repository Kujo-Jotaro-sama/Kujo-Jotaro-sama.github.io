<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>首页</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="robots" content="all,follow">
</head>
<body>

    <div class="page">
        <!-- Main Navbar-->
        <header class="header">
            <nav class="navbar">
                <!-- Search Box-->
                <div class="search-box">
                    <button class="dismiss"><i class="icon-close"></i></button>
                    <form id="searchForm" action="#" role="search">
                        <input type="search" placeholder="What are you looking for..." class="form-control">
                    </form>
                </div>
                <div class="container-fluid">
                    <div class="navbar-holder d-flex align-items-center justify-content-between">

                        <!-- Navbar Header-->
                        <div class="navbar-header">
                            <!-- Navbar Brand -->
                            <div style="margin-top: -16px; margin-bottom: -40px; margin-left: -12px">
                                <table style="width:100%">
                                    <tr>

                                        <td>
                                            <div id="logoHolder" style="background: url(/uploads/<asp:Literal runat=" server" Text="<%$ AppSettings:Username%>" />_logo.png) no-repeat; background-size:contain; width: 420px; height: 69px; margin: 0px;">
                            </div>
                            </td>

                            <td style="text-align:right; margin-top: 5px">
                            </td>
                            </tr>
                            </table>
                        </div>

                        <a style="margin-left: 300px;"></a>
                    </div>
                    <!-- Navbar Menu -->
                    <ul class="nav-menu list-unstyled d-flex flex-md-row align-items-md-center">
                        <li class="nav-item"> <label id="current-time" style="text-align:right; margin-top: 5px"></label></li>
                        <!-- Logout    -->
                        <li class="nav-item"><a href="login.aspx" class="nav-link logout"><span class="d-none d-sm-inline">注销</span><i class="fa fa-sign-out"></i></a></li>
                    </ul>


                </div>
    </div>
    </nav>
    </header>
    <div class="box">

        <div class="box1">



        </div>

    </div>
    <div class="page-content d-flex align-items-stretch">
        <table id="nav-bar-and-toggle">
            <tr>
                <td>
                    <!-- Side Navbar -->
                    <nav class="side-navbar">
                        <!-- Sidebar Header-->
                        <div class="sidebar-header d-flex align-items-center">
                            <div style="background-image:url(../img/CHControl.png) ; background-repeat:no-repeat;width:484px;height:58px; margin-top:9px"></div>
                        </div>
                        <!-- Sidebar Navidation Menus-->
                        <span class="heading">Main</span>
                        <div class="innerbox" style="overflow-y: scroll; height: 75vh;">

                            <ul class="list-unstyled">
                                <li><a href="Home.aspx"><i class="icon-home"></i>首页</a></li>
                                <li><a href="index_power.aspx"><i class="fa fa-tasks"></i>总能耗概览</a></li>
                                <li><a href="ProductionTimeAnalysis.aspx"><i class="fa fa-area-chart"></i>生产总能耗分析</a></li>
                                <li><a href="ProductionLineEnergyConsumptionAnalysis.aspx"><i class="fa fa-sellsy"></i>产线生产能耗分析</a></li>
                                <li><a href="RegionalEnergyConsumptionStatistics.aspx"><i class="icon-interface-windows"></i>回路损耗</a></li>
                                <li><a href="EnergyConsumptionRanking.aspx"><i class="fa fa-line-chart"></i>能耗排名</a></li>
                                <li><a href="RegionalEnergyConsumptionAnalysis.aspx"><i class="fa fa-pie-chart"></i>区域能耗分析</a></li>
                                <li><a href="EquipmentAnalysis.aspx"><i class="fa fa-dashboard"></i>设备能耗分析</a></li>
                                <li><a href="ProductivityAnalysis.aspx"><i class="fa fa-building"></i>产能分析</a></li>
                                <li><a href="Report.aspx"><i class="fa fa-desktop"></i>本地报表</a></li>
                            </ul>

                            <span class="heading">其他</span>
                            <ul class="list-unstyled">
                                <li>
                                    <a href="#exampledropdownDropdown11" aria-expanded="false" data-toggle="collapse"><i class="fa fa-cog"></i>系统设置</a>
                                    <ul id="exampledropdownDropdown11" class="collapse list-unstyled ">
                                        <li><a href="TotalEnergyConsumptionSettings.aspx"><i class="fa fa-cogs"></i>总能耗设置</a></li>
                                        <li><a href="LimitValueSetting.aspx"><i class="fa fa-cogs"></i>能耗限值设置</a></li>
                                        <li><a href="CapacityIntroduction.aspx"><i class="fa fa-cogs"></i>产能设置</a></li>
                                        <li><a href="ProductionTimSeetting.aspx"><i class="fa fa-cogs"></i>生产时间设置</a></li>
                                        <li><a href="ThemeSettings.aspx"><i class="fa fa-cogs"></i>系统主题设置</a></li>
                                    </ul>
                                </li>
                            </ul>
                        </div>
                    </nav>
                </td>
                <td>
                    <!--toggle button-->
                    <div id="toggle-btn" class="toggle-bar-padding">
                        <span style="position: relative; left: 12px; top: 50%" class="triangle"></span>
                    </div>
                </td>
            </tr>
        </table>
        <div class="content-inner">
            <table style="width: 100%">
                <tr>
                    <td style="width: 70%">
                        <section class="dashboard-counts no-padding-bottom">
                            <div class="container-fluid" style="padding-bottom: 0px; margin-bottom: 0px; padding-right: 1px">
                                <div class="card" style="width: 100%; height: 84vh; margin-bottom: 0px;">
                                    <div class="card-body" style="background-image: url(../img/bg.jpg);background-repeat:no-repeat;background-size:cover">
                                    </div>
                                </div>



                            </div>
                        </section>
                    </td>
                    <td style="width: 70%">
                        <section class="dashboard-counts no-padding-bottom">
                            <div class="container-fluid" style="padding-bottom: 0px; margin-bottom: 0px; padding-right: 1px">
                                <div class="card" style="width: 100%; height: 84vh; margin-bottom: 0px;">


                                    <table class="card" style="width: 100%;">
                                        <tr>
                                            <td style="font-size:18px;padding-left:20px;color:black">统计周期：</td>
                                            <td> <a id="today" href="#" class="btn btn-primary" style="width:80px" onclick="(function() {$('#loader-wrapper').show();}) (); load('当天');">当天</a></td>
                                            <td> <a id="month" href="#" class="btn btn-primary" style="width:80px" onclick="(function() {$('#loader-wrapper').show();}) (); load('本月');">本月</a></td>
                                            <td> <a id="year" href="#" class="btn btn-primary" style="width:80px" onclick="(function() {$('#loader-wrapper').show();}) (); load('今年');">今年</a></td>
                                            <td></td>
                                        </tr>
                                    </table>
                                    <div id="nesdiv" class="card-body" style="overflow-y: scroll; color:black">
                                    </div>
                                </div>
                            </div>
                        </section>


                    </td>

                </tr>
            </table>


            <footer class="main-footer">
                <table style="width: 100%; text-align: center">
                    <tr style="width: 100%;">
                        <td>
                            版权所有：广州中浩控制技术有限公司
                        </td>
                        <td>
                            地址：广州市先烈中路100号大院13号楼5层(510070) Tel:(8620) 66818328 FAX:(8620) 87686005
                        </td>
                    </tr>

                </table>
            </footer>

        </div>

    </div>



    </div>


</body>
</html>
