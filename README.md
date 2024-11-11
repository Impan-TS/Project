<div id="spinning2Div">
    <style>
        /* Optional: Add some basic styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }
        #spinning2Div {
            transform: scale(0.8);
            left: 50px;
            margin-top: 30px;
            position: relative;
            width: 100%;
            height: 100%;
            display: block; /* Change to block for testing */
        }
        .switch {
            cursor: pointer;
            display: inline-block;
            border-radius: 50%;
        }
    </style>

    <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.8.2/angular.min.js"></script>

    <div style="position: absolute; top: 15px; left: 130px; width: 1260px; height: 630px; border: 2px solid #C5C6D0; border-radius: 20px;"></div>

    <!-- Toggle Switches -->
    <div style="position:absolute; left:355px; top:332px;">
        <span class="switch" ng-click="switch1 = switch1 === 'on' ? 'off' : 'on'" style="background-color: {{switch1 === 'on' ? 'green' : 'red'}}; width: 30px; height: 30px;"></span>
    </div>
    <div style="position:absolute; left:376px; top:332px;">
        <span class="switch" ng-click="tripSwitch1 = tripSwitch1 === 'on' ? 'off' : 'on'" style="background-color: {{tripSwitch1 === 'on' ? 'yellow' : 'gray'}}; width: 20px; height: 20px;"></span>
    </div>

    <div style="position:absolute; left:595px; top:445px;">
        <span class="switch" ng-click="switch2 = switch2 === 'on' ? 'off' : 'on'" style="background-color: {{switch2 === 'on' ? 'green' : 'red'}}; width: 30px; height: 30px;"></span>
    </div>
    <div style="position:absolute; left:616px; top:445px;">
        <span class="switch" ng-click="tripSwitch2 = tripSwitch2 === 'on' ? 'off' : 'on'" style="background-color: {{tripSwitch2 === 'on' ? 'yellow' : 'gray'}}; width: 20px; height: 20px;"></span>
    </div>

    <div style="position:absolute; left:580px; top:333px;">
        <span class="switch" ng-click="switch3 = switch3 === 'on' ? 'off' : 'on'" style="background-color: {{switch3 === 'on' ? 'green' : 'red'}}; width: 30px; height: 30px;"></span>
    </div>
    <div style="position:absolute; left:601px; top:333px;">
        <span class="switch" ng-click="tripSwitch3 = tripSwitch3 === 'on' ? 'off' : 'on'" style="background-color: {{tripSwitch3 === 'on' ? 'yellow' : 'gray'}}; width: 20px; height: 20px;"></span>
    </div>

    <div style="position:absolute; left:578px; top:190px;">
        <span class="switch" ng-click="switch4 = switch4 === 'on' ? 'off' : 'on'" style="background-color: {{switch4 === 'on' ? 'green' : 'red'}}; width: 30px; height: 30px;"></span>
    </div>
    <div style="position:absolute; left:599px; top:190px;">
        <span class="switch" ng-click="tripSwitch4 = tripSwitch4 === 'on' ? 'off' : 'on'" style="background-color: {{tripSwitch4 === 'on' ? 'yellow' : 'gray'}}; width: 20px; height: 20px;"></span>
    </div>

    <div style="position:absolute; left:1087px; top:357px;">
        <span class="switch" ng-click="switch5 = switch5 === 'on' ? 'off' : 'on'" style="background-color: {{switch5 === 'on' ? 'green' : 'red'}}; width: 30px; height: 30px;"></span>
    </div>
    <div style="position:absolute; left:1108px; top:357px;">
        <span class="switch" ng-click="tripSwitch5 = tripSwitch5 === 'on' ? 'off' : 'on'" style="background-color: {{tripSwitch5 === 'on' ? 'yellow' : 'gray'}}; width: 20px; height: 20px;"></span>
    </div>

    <div style="position:absolute; left:1335px; top:450px;">
        <span class="switch" ng-click="switch6 = switch6 === 'on' ? 'off' : 'on'" style="background-color: {{switch6 === 'on' ? 'green' : 'red'}}; width: 30px; height: 30px;"></span>
    </div>
    <div style="position:absolute; left:1356px; top:450px;">
        <span class="switch" ng-click="tripSwitch6 = tripSwitch6 === 'on' ? 'off' : 'on'" style="background-color: {{tripSwitch6 === 'on' ? 'yellow' : 'gray'}}; width: 20px; height: 20px;"></span>
    </div>

    <script>
        // AngularJS application and controller
        angular.module('toggleApp', [])
            .controller('ToggleController', function($scope) {
                $scope.switch1 = 'off';
                $scope.tripSwitch1 = 'off';
                $scope.switch2 = 'off';
                $scope.tripSwitch2 = 'off';
                $scope.switch3 = 'off';
                $scope.tripSwitch3 = 'off';
                $scope.switch4 = 'off';
                $scope.tripSwitch4 = 'off';
                $scope.switch5 = 'off';
                $scope.tripSwitch5 = 'off';
                $scope.switch6 = 'off';
                $scope.tripSwitch6 = 'off';
            });
    </script>
</div>
