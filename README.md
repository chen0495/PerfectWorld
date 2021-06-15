# PerfectWorld
《完美世界》可视化

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Awesome-pyecharts</title>
            <script type="text/javascript" src="https://assets.pyecharts.org/assets/echarts.min.js"></script>
        <script type="text/javascript" src="https://assets.pyecharts.org/assets/echarts-wordcloud.min.js"></script>

</head>
<body>
    <div id="15c60e7c5e16422f94c83d6b3f15f461" class="chart-container" style="width:900px; height:500px;"></div>
    <script>
        var chart_15c60e7c5e16422f94c83d6b3f15f461 = echarts.init(
            document.getElementById('15c60e7c5e16422f94c83d6b3f15f461'), 'white', {renderer: 'canvas'});
        var option_15c60e7c5e16422f94c83d6b3f15f461 = {
    "animation": true,
    "animationThreshold": 2000,
    "animationDuration": 1000,
    "animationEasing": "cubicOut",
    "animationDelay": 0,
    "animationDurationUpdate": 300,
    "animationEasingUpdate": "cubicOut",
    "animationDelayUpdate": 0,
    "color": [
        "#c23531",
        "#2f4554",
        "#61a0a8",
        "#d48265",
        "#749f83",
        "#ca8622",
        "#bda29a",
        "#6e7074",
        "#546570",
        "#c4ccd3",
        "#f05b72",
        "#ef5b9c",
        "#f47920",
        "#905a3d",
        "#fab27b",
        "#2a5caa",
        "#444693",
        "#726930",
        "#b2d235",
        "#6d8346",
        "#ac6767",
        "#1d953f",
        "#6950a1",
        "#918597"
    ],
    "series": [
        {
            "type": "wordCloud",
            "shape": "diamond",
            "rotationRange": [
                0,
                0
            ],
            "rotationStep": 45,
            "girdSize": 20,
            "sizeRange": [
                20,
                100
            ],
            "data": [
                {
                    "name": "\u771f\u9f99",
                    "value": 3660,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(155,116,132)"
                        }
                    }
                },
                {
                    "name": "\u4ed9\u51f0",
                    "value": 1321,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(157,83,124)"
                        }
                    }
                },
                {
                    "name": "\u9cb2\u9e4f",
                    "value": 1366,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(97,147,27)"
                        }
                    }
                },
                {
                    "name": "\u6253\u795e\u77f3",
                    "value": 802,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(138,22,109)"
                        }
                    }
                },
                {
                    "name": "\u5929\u89d2\u8681",
                    "value": 693,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(82,7,46)"
                        }
                    }
                },
                {
                    "name": "\u96f7\u5e1d",
                    "value": 295,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(41,76,6)"
                        }
                    }
                },
                {
                    "name": "\u9e92\u9e9f",
                    "value": 332,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(0,48,92)"
                        }
                    }
                },
                {
                    "name": "\u86c4",
                    "value": 345,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(66,138,109)"
                        }
                    }
                },
                {
                    "name": "\u4e5d\u5e7d\u7353",
                    "value": 89,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(32,119,118)"
                        }
                    }
                },
                {
                    "name": "\u4e5d\u53f6\u5251\u8349",
                    "value": 4,
                    "textStyle": {
                        "normal": {
                            "color": "rgb(137,51,24)"
                        }
                    }
                }
            ],
            "drawOutOfBound": false,
            "textStyle": {
                "emphasis": {}
            }
        }
    ],
    "legend": [
        {
            "data": [],
            "selected": {},
            "show": true,
            "padding": 5,
            "itemGap": 10,
            "itemWidth": 25,
            "itemHeight": 14
        }
    ],
    "tooltip": {
        "show": true,
        "trigger": "item",
        "triggerOn": "mousemove|click",
        "axisPointer": {
            "type": "line"
        },
        "showContent": true,
        "alwaysShowContent": false,
        "showDelay": 0,
        "hideDelay": 100,
        "textStyle": {
            "fontSize": 14
        },
        "borderWidth": 0,
        "padding": 5
    },
    "title": [
        {
            "text": "WordCloud-shape-diamond",
            "padding": 5,
            "itemGap": 10
        }
    ]
};
        chart_15c60e7c5e16422f94c83d6b3f15f461.setOption(option_15c60e7c5e16422f94c83d6b3f15f461);
    </script>
</body>
</html>
