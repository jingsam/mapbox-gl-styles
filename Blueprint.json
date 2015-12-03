{
    "version": 8,
    "name": "Blue Print",
    "metadata": {
        "mapbox:groups": {
            "1442419828166.77": {
                "name": "water labels",
                "collapsed": true
            },
            "1442417536053.8835": {
                "name": "new roads",
                "collapsed": false
            },
            "1446067501448.8318": {
                "name": "bridge",
                "collapsed": true
            },
            "1442411971660.5637": {
                "name": "admins",
                "collapsed": true
            },
            "1442412003462.3938": {
                "name": "water",
                "collapsed": false
            },
            "1446072574542.3005": {
                "name": "poi labels",
                "collapsed": true
            },
            "1442412026707.74": {
                "name": "road labels",
                "collapsed": true
            },
            "1446061729146.9553": {
                "name": "roads",
                "collapsed": true
            },
            "1442411988988.8062": {
                "name": "roads",
                "collapsed": true
            },
            "1442411855944.8582": {
                "name": "marine_label",
                "collapsed": true
            },
            "1442411811866.782": {
                "name": "marine_label_lines"
            },
            "1442417652970.4246": {
                "name": "buildings",
                "collapsed": true
            },
            "1445985585732.7402": {
                "name": "roads",
                "collapsed": true
            },
            "1446075153820.7134": {
                "name": "tunnels",
                "collapsed": true
            },
            "1443114340389.3215": {
                "name": "this",
                "collapsed": true
            },
            "1442411843862.503": {
                "name": "mari"
            },
            "1442445584155.136": {
                "name": "city labels",
                "collapsed": true
            },
            "1442412011563.8718": {
                "name": "bridge",
                "collapsed": true
            },
            "1442411912812.8813": {
                "name": "place_labels",
                "collapsed": true
            }
        }
    },
    "center": [
        -71.06366265500988,
        42.36939251327766
    ],
    "zoom": 15.446456685541728,
    "bearing": 0,
    "pitch": 0,
    "sources": {
        "mapbox": {
            "url": "mapbox://mapbox.mapbox-streets-v6",
            "type": "vector"
        }
    },
    "sprite": "mapbox://sprites/maper/cihpxxwt8001jb0kpz9z559wm",
    "glyphs": "mapbox://fonts/maper/{fontstack}/{range}.pbf",
    "layers": [
        {
            "id": "background",
            "type": "background",
            "layout": {
                "visibility": "visible"
            },
            "paint": {
                "background-color": "#405CB1"
            },
            "interactive": true
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round",
                "line-round-limit": 4
            },
            "filter": [
                "==",
                "$type",
                "Polygon"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "water",
            "paint": {
                "line-color": "#E4EAF6",
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            7,
                            0
                        ],
                        [
                            13,
                            0.5
                        ],
                        [
                            16,
                            1.75
                        ],
                        [
                            18,
                            4
                        ]
                    ]
                },
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            7,
                            0
                        ],
                        [
                            12,
                            1
                        ]
                    ]
                }
            },
            "source-layer": "water"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "Polygon",
                    "LineString"
                ],
                [
                    "!in",
                    "class",
                    "fence",
                    "hedge"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "barrier-line",
            "paint": {
                "line-color": "#E4EAF6",
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            13,
                            0.25
                        ],
                        [
                            16,
                            1.25
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                }
            },
            "source-layer": "barrier_line"
        },
        {
            "interactive": true,
            "minzoom": 13,
            "layout": {
                "line-cap": "square",
                "line-join": "miter",
                "visibility": "visible",
                "line-miter-limit": 2
            },
            "metadata": {
                "mapbox:group": "1442417652970.4246"
            },
            "filter": [
                "in",
                "$type",
                "Polygon",
                "LineString"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "building_outline",
            "paint": {
                "line-color": "#E4EAF6",
                "line-width": {
                    "base": 1,
                    "stops": [
                        [
                            15,
                            0.5
                        ],
                        [
                            22,
                            1
                        ]
                    ]
                }
            },
            "source-layer": "building"
        },
        {
            "interactive": true,
            "minzoom": 13,
            "layout": {
                "line-cap": "round",
                "line-join": "round",
                "visibility": "visible",
                "line-round-limit": 2
            },
            "metadata": {
                "mapbox:group": "1442417652970.4246"
            },
            "filter": [
                "in",
                "$type",
                "Polygon",
                "Point",
                "LineString"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "landuse",
            "paint": {
                "line-color": "#E4EAF6",
                "line-width": {
                    "base": 1,
                    "stops": [
                        [
                            15,
                            0.5
                        ],
                        [
                            22,
                            1
                        ]
                    ]
                },
                "line-opacity": 0.5
            },
            "source-layer": "landuse"
        },
        {
            "layout": {
                "visibility": "visible"
            },
            "metadata": {
                "mapbox:group": "1442417652970.4246"
            },
            "type": "line",
            "source": "mapbox",
            "id": "aeroway",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.5,
                    "stops": [
                        [
                            10,
                            0
                        ],
                        [
                            12,
                            1
                        ]
                    ]
                },
                "line-width": 0.5
            },
            "source-layer": "aeroway",
            "interactive": true
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "motorway_link"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway_link case copy 1",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            10.99,
                            0
                        ],
                        [
                            11,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.2,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                },
                "line-dasharray": [
                    3,
                    3
                ]
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "in",
                    "class",
                    "driveway",
                    "service"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "service-driveway case copy 1",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            14,
                            0.5
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                },
                "line-dasharray": [
                    3,
                    3
                ]
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "street_limited"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street limited tunnel case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            13,
                            0
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                },
                "line-dasharray": [
                    3,
                    3
                ]
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "==",
                "class",
                "street"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street tunnel case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            13,
                            0
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                },
                "line-dasharray": [
                    3,
                    3
                ]
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "!=",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "main tunnel case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            8,
                            0
                        ],
                        [
                            10,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.2,
                    "stops": [
                        [
                            10,
                            0.5
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                },
                "line-dasharray": [
                    3,
                    3
                ],
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            8.5,
                            0.5
                        ],
                        [
                            10,
                            0.75
                        ],
                        [
                            18,
                            26
                        ]
                    ]
                }
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "==",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "trunk tunnel case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5.9,
                            0
                        ],
                        [
                            6,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                },
                "line-dasharray": [
                    3,
                    3
                ]
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "==",
                "class",
                "motorway"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway tunnel case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5.5,
                            0
                        ],
                        [
                            6,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            16,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                },
                "line-dasharray": [
                    3,
                    3
                ]
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "all",
                    [
                        "==",
                        "class",
                        "main"
                    ],
                    [
                        "==",
                        "type",
                        "driveway"
                    ]
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "service-driveway tunnel",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            14,
                            0.5
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "id": "service-driveway tunnel (lighten)",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 0.25,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            14,
                            0.5
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                },
                "line-blur": 8
            },
            "ref": "service-driveway tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "motorway_link"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway_link tunnel",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "id": "motorway_link tunnel case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 0.5,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                },
                "line-blur": 8
            },
            "ref": "motorway_link tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "street_limited"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street limited tunnel",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "id": "street limited tunnel (lighten)",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 0.5,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                },
                "line-blur": 8
            },
            "ref": "street limited tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "street"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street tunnel",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "id": "street tunnel (lighten)",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 0.25,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "ref": "street tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "!=",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "main tunnel",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            8.5,
                            0.5
                        ],
                        [
                            10,
                            0.75
                        ],
                        [
                            18,
                            26
                        ]
                    ]
                }
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "id": "main tunnel (lighten)",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 0.25,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            8.5,
                            0.5
                        ],
                        [
                            10,
                            0.75
                        ],
                        [
                            18,
                            26
                        ]
                    ]
                },
                "line-blur": 8
            },
            "ref": "main tunnel case"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "==",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "trunk tunnel",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "id": "trunk tunnel (lighten)",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 0.25,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "ref": "trunk tunnel"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "filter": [
                "==",
                "class",
                "motorway"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway tunnel",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "source-layer": "tunnel"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446075153820.7134"
            },
            "id": "motorway tunnel (lighten)",
            "paint": {
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                },
                "line-color": "#E4EAF6",
                "line-opacity": 0.25,
                "line-blur": 8
            },
            "ref": "motorway tunnel case"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "path"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "path",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            15,
                            0
                        ],
                        [
                            15.25,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            15,
                            1
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                },
                "line-dasharray": {
                    "base": 1,
                    "stops": [
                        [
                            15,
                            [
                                0.1,
                                2.25
                            ]
                        ],
                        [
                            16,
                            [
                                0.1,
                                2.6
                            ]
                        ],
                        [
                            17,
                            [
                                0.1,
                                2.45
                            ]
                        ],
                        [
                            18,
                            [
                                0.1,
                                2.3
                            ]
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "street"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street low",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            11,
                            0
                        ],
                        [
                            12.25,
                            1
                        ],
                        [
                            14,
                            1
                        ],
                        [
                            14.01,
                            0
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            1.5
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "street_limited"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street-limited low",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            11,
                            0
                        ],
                        [
                            11.25,
                            1
                        ],
                        [
                            14,
                            1
                        ],
                        [
                            14.25,
                            0
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.2,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            0.75
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "motorway_link"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway_link case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            10.99,
                            0
                        ],
                        [
                            11,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.2,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "in",
                    "class",
                    "driveway",
                    "service"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "service-driveway case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            14,
                            0.5
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "id": "street limited case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            13,
                            0
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "ref": "street-limited low"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "==",
                "class",
                "street"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            13,
                            0
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "!=",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "main case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            8,
                            0
                        ],
                        [
                            10,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.2,
                    "stops": [
                        [
                            10,
                            0.5
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                },
                "line-dasharray": [
                    1,
                    0
                ],
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            8.5,
                            0.5
                        ],
                        [
                            10,
                            0.75
                        ],
                        [
                            18,
                            26
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "==",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "trunk case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5.9,
                            0
                        ],
                        [
                            6,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "filter": [
                "==",
                "class",
                "motorway"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway-case",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5.5,
                            0
                        ],
                        [
                            6,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            16,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "source-layer": "road"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "id": "service-driveway",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            14,
                            0.5
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "ref": "service-driveway case"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "id": "motorway_link",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "ref": "motorway_link case"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "id": "street limited",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "ref": "street-limited low"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "id": "street",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "ref": "street low"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "id": "main",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            8.5,
                            0.5
                        ],
                        [
                            10,
                            0.75
                        ],
                        [
                            18,
                            26
                        ]
                    ]
                }
            },
            "ref": "main case"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "id": "trunk",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "ref": "trunk case"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446061729146.9553"
            },
            "id": "motorway",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "ref": "motorway-case"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "path"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "path bg copy",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            15,
                            0
                        ],
                        [
                            15.25,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            15,
                            2
                        ],
                        [
                            18,
                            7
                        ]
                    ]
                },
                "line-dasharray": [
                    1,
                    0
                ]
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "id": "path bg copy (darken)",
            "paint": {
                "line-color": "rgba(0,0,0,1)",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            15,
                            0
                        ],
                        [
                            22,
                            0.1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            15,
                            2
                        ],
                        [
                            18,
                            7
                        ]
                    ]
                },
                "line-dasharray": [
                    1,
                    0
                ]
            },
            "ref": "path bg copy"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "path"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "path copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            15,
                            0
                        ],
                        [
                            15.25,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            15,
                            1
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                },
                "line-dasharray": {
                    "base": 1,
                    "stops": [
                        [
                            15,
                            [
                                0.1,
                                2.25
                            ]
                        ],
                        [
                            16,
                            [
                                0.1,
                                2.6
                            ]
                        ],
                        [
                            17,
                            [
                                0.1,
                                2.45
                            ]
                        ],
                        [
                            18,
                            [
                                0.1,
                                2.3
                            ]
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "street"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street low copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            11,
                            0
                        ],
                        [
                            12.25,
                            1
                        ],
                        [
                            14,
                            1
                        ],
                        [
                            14.01,
                            0
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            1.5
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "street_limited"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street-limited low copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            11,
                            0
                        ],
                        [
                            11.25,
                            1
                        ],
                        [
                            14,
                            1
                        ],
                        [
                            14.01,
                            0
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "motorway_link"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway_link case copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            10.99,
                            0
                        ],
                        [
                            11,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.2,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "in",
                    "class",
                    "driveway",
                    "service"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "service-driveway case copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            14,
                            0.5
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "street_limited"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street limited case copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            13,
                            0
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "==",
                "class",
                "street"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "street case copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.75
                        ],
                        [
                            20,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            13,
                            0
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "!=",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "main case copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            8,
                            0
                        ],
                        [
                            10,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.2,
                    "stops": [
                        [
                            10,
                            0.5
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                },
                "line-dasharray": [
                    1,
                    0
                ],
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            8.5,
                            0.5
                        ],
                        [
                            10,
                            0.75
                        ],
                        [
                            18,
                            26
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "==",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "trunk case copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5.9,
                            0
                        ],
                        [
                            6,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "==",
                "class",
                "motorway"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway-case copy",
            "paint": {
                "line-color": "#E4EAF6",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5.5,
                            0
                        ],
                        [
                            6,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            16,
                            2
                        ]
                    ]
                },
                "line-gap-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "butt",
                "line-join": "miter"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "all",
                    [
                        "==",
                        "class",
                        "main"
                    ],
                    [
                        "==",
                        "type",
                        "driveway"
                    ]
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "service-driveway copy",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            14,
                            0.5
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "in",
                    "$type",
                    "LineString",
                    "Polygon",
                    "Point"
                ],
                [
                    "==",
                    "class",
                    "motorway_link"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway_link copy",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": 1,
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "id": "street limited copy",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            12
                        ]
                    ]
                }
            },
            "ref": "street-limited low copy"
        },
        {
            "interactive": true,
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "id": "street copy",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            13.99,
                            0
                        ],
                        [
                            14,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            12.5,
                            0.5
                        ],
                        [
                            14,
                            2
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "ref": "street low copy"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "!=",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "main copy",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            8.5,
                            0.5
                        ],
                        [
                            10,
                            0.75
                        ],
                        [
                            18,
                            26
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "all",
                [
                    "==",
                    "class",
                    "main"
                ],
                [
                    "==",
                    "type",
                    "trunk"
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "trunk copy",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-cap": "round",
                "line-join": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1446067501448.8318"
            },
            "filter": [
                "==",
                "class",
                "motorway"
            ],
            "type": "line",
            "source": "mapbox",
            "id": "motorway copy",
            "paint": {
                "line-color": "#405CB1",
                "line-opacity": {
                    "base": 1.2,
                    "stops": [
                        [
                            5,
                            0
                        ],
                        [
                            5.5,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1.5,
                    "stops": [
                        [
                            5,
                            0.75
                        ],
                        [
                            18,
                            32
                        ]
                    ]
                }
            },
            "source-layer": "bridge"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-join": "bevel"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1442411971660.5637"
            },
            "filter": [
                "all",
                [
                    ">=",
                    "admin_level",
                    3
                ],
                [
                    "==",
                    "maritime",
                    0
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "state",
            "paint": {
                "line-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            2,
                            0
                        ],
                        [
                            3,
                            1
                        ]
                    ]
                },
                "line-width": {
                    "base": 1,
                    "stops": [
                        [
                            7,
                            0.75
                        ],
                        [
                            12,
                            1.5
                        ]
                    ]
                },
                "line-color": "#E4EAF6"
            },
            "source-layer": "admin"
        },
        {
            "interactive": true,
            "minzoom": 1,
            "layout": {
                "visibility": "visible",
                "line-join": "round",
                "line-cap": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1442411971660.5637"
            },
            "filter": [
                "all",
                [
                    "==",
                    "admin_level",
                    2
                ],
                [
                    "==",
                    "maritime",
                    0
                ],
                [
                    "==",
                    "disputed",
                    0
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "countries",
            "paint": {
                "line-dasharray": [
                    1,
                    0
                ],
                "line-opacity": 1,
                "line-width": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            0.5
                        ],
                        [
                            2,
                            1
                        ],
                        [
                            8,
                            5
                        ]
                    ]
                },
                "line-color": "#E4EAF6"
            },
            "source-layer": "admin"
        },
        {
            "interactive": true,
            "layout": {
                "visibility": "visible",
                "line-join": "round",
                "line-cap": "round"
            },
            "nextDropPoint": false,
            "metadata": {
                "mapbox:group": "1442411971660.5637"
            },
            "filter": [
                "all",
                [
                    "==",
                    "maritime",
                    1
                ],
                [
                    "==",
                    "admin_level",
                    2
                ]
            ],
            "type": "line",
            "source": "mapbox",
            "id": "maritime",
            "paint": {
                "line-width": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            0.5
                        ],
                        [
                            2,
                            1
                        ],
                        [
                            8,
                            5
                        ]
                    ]
                },
                "line-opacity": 1,
                "line-color": "#E4EAF6"
            },
            "source-layer": "admin"
        },
        {
            "interactive": true,
            "minzoom": 12,
            "layout": {
                "symbol-placement": "line",
                "text-field": "{name_en}",
                "text-font": [
                    "Kievit Offc Pro Bold",
                    "Arial Unicode MS Bold"
                ],
                "text-transform": "uppercase",
                "text-letter-spacing": 0,
                "text-padding": 0,
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            8,
                            8
                        ],
                        [
                            20,
                            15
                        ]
                    ]
                },
                "visibility": "visible"
            },
            "metadata": {
                "mapbox:group": "1442412026707.74"
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "LineString"
                ],
                [
                    "!in",
                    "class",
                    "motorway",
                    "main",
                    "street_limited",
                    "street"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "road-label-sm",
            "paint": {
                "text-halo-color": "#405CB1",
                "text-halo-width": 3,
                "text-color": "rgba(228,234,246,1)"
            },
            "source-layer": "road_label"
        },
        {
            "interactive": true,
            "layout": {
                "symbol-placement": "line",
                "text-field": "{name_en}",
                "text-font": [
                    "Kievit Offc Pro Bold",
                    "Arial Unicode MS Bold"
                ],
                "text-transform": "uppercase",
                "text-letter-spacing": 0,
                "text-padding": 0,
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            8,
                            8
                        ],
                        [
                            20,
                            16
                        ]
                    ]
                },
                "visibility": "visible"
            },
            "metadata": {
                "mapbox:group": "1442412026707.74"
            },
            "filter": [
                "in",
                "class",
                "street",
                "street_limited"
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "road-label-med",
            "paint": {
                "text-halo-color": "#405CB1",
                "text-halo-width": 3.5,
                "text-color": "rgba(228,234,246,1)"
            },
            "source-layer": "road_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            8,
                            8
                        ],
                        [
                            20,
                            17
                        ]
                    ]
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": false,
                "text-transform": "uppercase",
                "text-font": [
                    "Kievit Offc Pro Bold",
                    "Arial Unicode MS Bold"
                ],
                "symbol-placement": "line",
                "text-padding": 0,
                "visibility": "visible",
                "text-field": "{name_en}",
                "text-letter-spacing": 0
            },
            "metadata": {
                "mapbox:group": "1442412026707.74"
            },
            "filter": [
                "in",
                "class",
                "motorway",
                "main"
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "road-label-large",
            "paint": {
                "text-halo-color": "#405CB1",
                "text-halo-width": 4,
                "text-color": "rgba(228,234,246,1)"
            },
            "source-layer": "road_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-font": [
                    "Kievit Offc Pro Light",
                    "Arial Unicode MS Regular"
                ],
                "visibility": "visible",
                "text-field": {
                    "base": 1,
                    "stops": [
                        [
                            12,
                            ""
                        ],
                        [
                            13,
                            "{name_en}"
                        ]
                    ]
                },
                "text-max-width": 9,
                "text-size": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            14
                        ],
                        [
                            18,
                            36
                        ]
                    ]
                }
            },
            "metadata": {
                "mapbox:group": "1446072574542.3005"
            },
            "filter": [
                "all",
                [
                    "in",
                    "maki",
                    "airport",
                    "heliport",
                    "rocket"
                ],
                [
                    "in",
                    "scalerank",
                    2,
                    1
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "airport-label copy",
            "paint": {
                "text-color": "#e4eaf6",
                "text-halo-color": "#405CB1",
                "text-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            12,
                            0
                        ],
                        [
                            12.5,
                            1
                        ]
                    ]
                },
                "text-halo-blur": 0,
                "text-halo-width": {
                    "base": 1.4,
                    "stops": [
                        [
                            14,
                            2
                        ],
                        [
                            15,
                            6
                        ]
                    ]
                }
            },
            "source-layer": "poi_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-max-width": 8,
                "visibility": "visible",
                "text-field": "{name_en}",
                "text-font": [
                    "Kievit Offc Pro Light",
                    "Arial Unicode MS Regular"
                ],
                "text-size": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            10
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "metadata": {
                "mapbox:group": "1446072574542.3005"
            },
            "filter": [
                "all",
                [
                    "==",
                    "maki",
                    "park"
                ],
                [
                    "in",
                    "scalerank",
                    1,
                    2,
                    3,
                    4
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "poi-parks-scalerank1-3",
            "paint": {
                "text-color": "#e4eaf6",
                "text-halo-color": "#405CB1",
                "text-halo-width": {
                    "base": 1.4,
                    "stops": [
                        [
                            14,
                            2
                        ],
                        [
                            15,
                            6
                        ]
                    ]
                },
                "text-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            14,
                            0
                        ],
                        [
                            14.5,
                            1
                        ]
                    ]
                }
            },
            "source-layer": "poi_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-max-width": 8,
                "visibility": "visible",
                "text-field": "{name_en}",
                "text-font": [
                    "Kievit Offc Pro Light",
                    "Arial Unicode MS Regular"
                ],
                "text-size": {
                    "base": 1.5,
                    "stops": [
                        [
                            12,
                            10
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                }
            },
            "metadata": {
                "mapbox:group": "1446072574542.3005"
            },
            "filter": [
                "all",
                [
                    "!in",
                    "maki",
                    "rail-light",
                    "rail-metro",
                    "rail",
                    "airport",
                    "airfield",
                    "heliport",
                    "rocket",
                    "park",
                    "golf",
                    "cemetary",
                    "zoo",
                    "campsite",
                    "swimming",
                    "dog-park"
                ],
                [
                    "in",
                    "scalerank",
                    1,
                    2,
                    3
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "poi-scalerank1-3",
            "paint": {
                "text-color": "#e4eaf6",
                "text-halo-color": "#405CB1",
                "text-opacity": {
                    "base": 1,
                    "stops": [
                        [
                            14,
                            0
                        ],
                        [
                            14.5,
                            1
                        ]
                    ]
                },
                "text-halo-width": {
                    "base": 1.4,
                    "stops": [
                        [
                            14,
                            2
                        ],
                        [
                            15,
                            6
                        ]
                    ]
                }
            },
            "source-layer": "poi_label"
        },
        {
            "interactive": true,
            "minzoom": 10,
            "layout": {
                "text-line-height": 0.8,
                "text-size": {
                    "stops": [
                        [
                            12,
                            14
                        ],
                        [
                            16,
                            22
                        ]
                    ]
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": true,
                "text-transform": "none",
                "text-font": [
                    "Kievit Offc Pro Black Italic",
                    "Arial Unicode MS Bold"
                ],
                "visibility": "visible",
                "text-field": "{name_en}",
                "text-letter-spacing": 0.1,
                "text-max-width": 5
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "Point"
                ],
                [
                    "in",
                    "type",
                    "suburb",
                    "neighbourhood"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "place_label_neighborhood",
            "paint": {
                "text-color": "#405CB1",
                "text-halo-color": "#fff",
                "text-opacity": 1,
                "text-halo-blur": 0,
                "text-halo-width": {
                    "base": 1,
                    "stops": [
                        [
                            8,
                            0.75
                        ],
                        [
                            18,
                            2
                        ]
                    ]
                }
            },
            "source-layer": "place_label"
        },
        {
            "interactive": true,
            "minzoom": 12,
            "layout": {
                "text-font": [
                    "Kievit Offc Pro Light Italic",
                    "Arial Unicode MS Regular"
                ],
                "visibility": "visible",
                "symbol-placement": "line",
                "text-field": "{name_en}",
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            13,
                            14
                        ],
                        [
                            18,
                            18
                        ]
                    ]
                },
                "text-transform": "none"
            },
            "metadata": {
                "mapbox:group": "1442419828166.77"
            },
            "filter": [
                "==",
                "class",
                "river"
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "waterway-label",
            "paint": {
                "text-halo-width": 5,
                "text-halo-color": "#405CB1",
                "text-color": "#e4eaf6"
            },
            "source-layer": "waterway_label"
        },
        {
            "interactive": true,
            "minzoom": 5,
            "layout": {
                "text-font": [
                    "Kievit Offc Pro Italic",
                    "Arial Unicode MS Regular"
                ],
                "visibility": "visible",
                "text-field": "{name_en}",
                "text-max-width": 7,
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            13,
                            12
                        ],
                        [
                            18,
                            16
                        ]
                    ]
                }
            },
            "metadata": {
                "mapbox:group": "1442419828166.77"
            },
            "type": "symbol",
            "source": "mapbox",
            "id": "water-label",
            "paint": {
                "text-halo-width": 4,
                "text-halo-color": "#405CB1",
                "text-color": "#e4eaf6"
            },
            "source-layer": "water_label"
        },
        {
            "interactive": true,
            "minzoom": 10,
            "layout": {
                "text-line-height": 0.8,
                "text-size": {
                    "stops": [
                        [
                            11,
                            18
                        ],
                        [
                            14,
                            34
                        ]
                    ],
                    "base": 0.9
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": true,
                "text-ignore-placement": false,
                "text-transform": "uppercase",
                "text-font": [
                    "Kievit Offc Pro Black",
                    "Arial Unicode MS Bold"
                ],
                "visibility": "visible",
                "text-field": "{name_en}",
                "text-letter-spacing": 0,
                "text-max-width": 5
            },
            "metadata": {
                "mapbox:group": "1442445584155.136"
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "Point"
                ],
                [
                    "==",
                    "type",
                    "town"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "place_label_city-sm",
            "paint": {
                "text-color": "rgba(255,255,255,1)",
                "text-halo-color": "#405CB1",
                "text-opacity": 1,
                "text-halo-blur": 0,
                "text-halo-width": {
                    "base": 1,
                    "stops": [
                        [
                            5,
                            6
                        ],
                        [
                            14,
                            4
                        ]
                    ]
                }
            },
            "source-layer": "place_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-line-height": 0.85,
                "text-size": {
                    "stops": [
                        [
                            4,
                            20
                        ],
                        [
                            10,
                            34
                        ]
                    ],
                    "base": 0.9
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": true,
                "text-transform": "uppercase",
                "text-font": [
                    "Kievit Offc Pro Black",
                    "Arial Unicode MS Bold"
                ],
                "visibility": "visible",
                "text-offset": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            [
                                0,
                                -0.2
                            ]
                        ],
                        [
                            6,
                            [
                                0,
                                0
                            ]
                        ]
                    ]
                },
                "text-anchor": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            "bottom"
                        ],
                        [
                            6,
                            "center"
                        ]
                    ]
                },
                "text-field": "{name_en}",
                "text-max-width": 5
            },
            "metadata": {
                "mapbox:group": "1442445584155.136"
            },
            "maxzoom": 16,
            "filter": [
                "all",
                [
                    "==",
                    "type",
                    "city"
                ],
                [
                    ">",
                    "scalerank",
                    4
                ],
                [
                    "in",
                    "ldir",
                    "N",
                    "W",
                    "NW",
                    "NE"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "place_label_city_small_n_copy",
            "paint": {
                "text-color": "rgba(255,255,255,1)",
                "text-halo-color": "#405CB1",
                "text-halo-width": {
                    "base": 1,
                    "stops": [
                        [
                            5,
                            7
                        ],
                        [
                            14,
                            5
                        ]
                    ]
                },
                "text-halo-blur": 0
            },
            "source-layer": "place_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-line-height": 0.85,
                "text-size": {
                    "stops": [
                        [
                            4,
                            20
                        ],
                        [
                            5,
                            34
                        ],
                        [
                            9,
                            34
                        ],
                        [
                            10,
                            34
                        ],
                        [
                            10,
                            34
                        ]
                    ],
                    "base": 0.9
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": true,
                "text-transform": "uppercase",
                "text-font": [
                    "Kievit Offc Pro Black",
                    "Arial Unicode MS Bold"
                ],
                "symbol-placement": "point",
                "text-justify": "center",
                "visibility": "visible",
                "text-offset": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            [
                                0,
                                0.1
                            ]
                        ],
                        [
                            6,
                            [
                                0,
                                0
                            ]
                        ]
                    ]
                },
                "text-anchor": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            "top"
                        ],
                        [
                            6,
                            "center"
                        ]
                    ]
                },
                "text-field": "{name_en}",
                "text-max-width": {
                    "base": 1,
                    "stops": [
                        [
                            7,
                            5
                        ],
                        [
                            15,
                            7
                        ]
                    ]
                }
            },
            "metadata": {
                "mapbox:group": "1442445584155.136"
            },
            "maxzoom": 16,
            "filter": [
                "all",
                [
                    "==",
                    "type",
                    "city"
                ],
                [
                    ">",
                    "scalerank",
                    4
                ],
                [
                    "in",
                    "ldir",
                    "S",
                    "E",
                    "SE",
                    "SW"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "place_label_city_small_s_copy",
            "paint": {
                "text-color": "#fff",
                "text-halo-color": "#405CB1",
                "text-halo-width": {
                    "base": 1,
                    "stops": [
                        [
                            5,
                            5
                        ],
                        [
                            14,
                            8
                        ]
                    ]
                },
                "text-halo-blur": 0,
                "text-opacity": 1
            },
            "source-layer": "place_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-line-height": 0.85,
                "text-size": {
                    "stops": [
                        [
                            4,
                            20
                        ],
                        [
                            10,
                            34
                        ]
                    ],
                    "base": 0.9
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": true,
                "text-transform": "uppercase",
                "text-font": [
                    "Kievit Offc Pro Black",
                    "Arial Unicode MS Bold"
                ],
                "visibility": "visible",
                "text-offset": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            [
                                0,
                                0.1
                            ]
                        ],
                        [
                            6,
                            [
                                0,
                                0
                            ]
                        ]
                    ]
                },
                "text-anchor": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            "top"
                        ],
                        [
                            6,
                            "center"
                        ]
                    ]
                },
                "text-field": "{name_en}",
                "text-max-width": 5
            },
            "metadata": {
                "mapbox:group": "1442445584155.136"
            },
            "maxzoom": 16,
            "filter": [
                "all",
                [
                    "==",
                    "type",
                    "city"
                ],
                [
                    "<=",
                    "scalerank",
                    4
                ],
                [
                    ">",
                    "scalerank",
                    1
                ],
                [
                    "in",
                    "ldir",
                    "S",
                    "E",
                    "SE",
                    "SW"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "place_label_city_medium_s_copy",
            "paint": {
                "text-color": "rgba(252,252,252,1)",
                "text-halo-color": "#405CB1",
                "text-halo-width": {
                    "base": 1,
                    "stops": [
                        [
                            5,
                            6
                        ],
                        [
                            14,
                            4
                        ]
                    ]
                },
                "text-halo-blur": 0
            },
            "source-layer": "place_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-line-height": 0.85,
                "text-size": {
                    "stops": [
                        [
                            4,
                            20
                        ],
                        [
                            10,
                            34
                        ]
                    ],
                    "base": 0.9
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": true,
                "text-ignore-placement": false,
                "text-transform": "uppercase",
                "text-font": [
                    "Kievit Offc Pro Black",
                    "Arial Unicode MS Bold"
                ],
                "visibility": "visible",
                "text-offset": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            [
                                0,
                                -0.2
                            ]
                        ],
                        [
                            6,
                            [
                                0,
                                0
                            ]
                        ]
                    ]
                },
                "text-anchor": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            "bottom"
                        ],
                        [
                            6,
                            "center"
                        ]
                    ]
                },
                "text-field": "{name_en}",
                "text-max-width": 5
            },
            "metadata": {
                "mapbox:group": "1442445584155.136"
            },
            "maxzoom": 16,
            "filter": [
                "all",
                [
                    "==",
                    "type",
                    "city"
                ],
                [
                    "<=",
                    "scalerank",
                    4
                ],
                [
                    ">",
                    "scalerank",
                    1
                ],
                [
                    "in",
                    "ldir",
                    "N",
                    "W",
                    "NW",
                    "NE"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "place_label_city_medium_n_copy",
            "paint": {
                "text-color": "rgba(255,255,255,1)",
                "text-halo-color": "#405CB1",
                "text-halo-width": {
                    "base": 1,
                    "stops": [
                        [
                            5,
                            6
                        ],
                        [
                            14,
                            4
                        ]
                    ]
                },
                "text-halo-blur": 0
            },
            "source-layer": "place_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-line-height": 0.85,
                "text-size": {
                    "stops": [
                        [
                            4,
                            20
                        ],
                        [
                            10,
                            34
                        ]
                    ],
                    "base": 0.9
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": true,
                "text-transform": "uppercase",
                "text-font": [
                    "Kievit Offc Pro Black",
                    "Arial Unicode MS Bold"
                ],
                "text-padding": 1,
                "visibility": "visible",
                "text-offset": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            [
                                0,
                                -0.2
                            ]
                        ],
                        [
                            6,
                            [
                                0,
                                0
                            ]
                        ]
                    ]
                },
                "text-rotation-alignment": "viewport",
                "text-anchor": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            "bottom"
                        ],
                        [
                            6,
                            "center"
                        ]
                    ]
                },
                "text-field": "{name_en}",
                "text-max-width": 5
            },
            "metadata": {
                "mapbox:group": "1442445584155.136"
            },
            "maxzoom": 16,
            "filter": [
                "all",
                [
                    "<=",
                    "scalerank",
                    1
                ],
                [
                    "in",
                    "ldir",
                    "N",
                    "NE",
                    "NW",
                    "W"
                ],
                [
                    "==",
                    "type",
                    "city"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "place_label_city_large_n_copy",
            "paint": {
                "text-color": "rgba(255,255,255,1)",
                "text-halo-color": "#405CB1",
                "text-halo-blur": 0,
                "text-halo-width": {
                    "base": 1,
                    "stops": [
                        [
                            5,
                            6
                        ],
                        [
                            14,
                            4
                        ]
                    ]
                }
            },
            "source-layer": "place_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-line-height": 0.85,
                "text-size": {
                    "stops": [
                        [
                            4,
                            20
                        ],
                        [
                            10,
                            34
                        ]
                    ],
                    "base": 0.9
                },
                "text-allow-overlap": false,
                "symbol-avoid-edges": false,
                "text-ignore-placement": false,
                "text-transform": "uppercase",
                "text-font": [
                    "Kievit Offc Pro Black",
                    "Arial Unicode MS Bold"
                ],
                "text-padding": 1,
                "visibility": "visible",
                "text-offset": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            [
                                0,
                                0.1
                            ]
                        ],
                        [
                            6,
                            [
                                0,
                                0
                            ]
                        ]
                    ]
                },
                "text-anchor": {
                    "base": 1,
                    "stops": [
                        [
                            0,
                            "top"
                        ],
                        [
                            6,
                            "center"
                        ]
                    ]
                },
                "text-field": "{name_en}",
                "text-max-width": 5
            },
            "metadata": {
                "mapbox:group": "1442445584155.136"
            },
            "maxzoom": 16,
            "filter": [
                "all",
                [
                    "==",
                    "type",
                    "city"
                ],
                [
                    "<=",
                    "scalerank",
                    1
                ],
                [
                    "in",
                    "ldir",
                    "S",
                    "SE",
                    "SW",
                    "E"
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "place_label_city_large_s_copy",
            "paint": {
                "text-color": "rgba(255,255,255,1)",
                "text-halo-color": "#405CB1",
                "text-halo-width": {
                    "base": 1,
                    "stops": [
                        [
                            5,
                            6
                        ],
                        [
                            14,
                            4
                        ]
                    ]
                },
                "text-halo-blur": 0
            },
            "source-layer": "place_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-max-width": 8,
                "visibility": "visible",
                "symbol-placement": "point",
                "text-field": "{name_en}",
                "text-line-height": 1.2,
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            3,
                            13
                        ],
                        [
                            5,
                            18
                        ]
                    ]
                },
                "text-font": [
                    "Kievit Offc Pro Italic",
                    "Arial Unicode MS Regular"
                ],
                "text-letter-spacing": 0.25
            },
            "metadata": {
                "mapbox:group": "1442411855944.8582"
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "Point"
                ],
                [
                    "==",
                    "labelrank",
                    3
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "marine_label_point_3",
            "paint": {
                "text-color": "#e4eaf6",
                "text-opacity": 0.25,
                "text-halo-color": "#405CB1",
                "text-halo-width": 1
            },
            "source-layer": "marine_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-max-width": 8,
                "visibility": "visible",
                "symbol-placement": "point",
                "text-field": "{name_en}",
                "text-line-height": 1.2,
                "text-letter-spacing": 0.4,
                "text-font": [
                    "Kievit Offc Pro Italic",
                    "Arial Unicode MS Regular"
                ],
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            3,
                            15
                        ],
                        [
                            4,
                            20
                        ]
                    ]
                }
            },
            "metadata": {
                "mapbox:group": "1442411855944.8582"
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "Point"
                ],
                [
                    "==",
                    "labelrank",
                    2
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "marine_label_point_2",
            "paint": {
                "text-color": "#e4eaf6",
                "text-opacity": 0.25,
                "text-halo-color": "#405CB1",
                "text-halo-width": 1
            },
            "source-layer": "marine_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-max-width": 4,
                "visibility": "visible",
                "symbol-placement": "point",
                "text-field": "{name_en}",
                "text-line-height": 1.2,
                "text-letter-spacing": 0.4,
                "text-font": [
                    "Kievit Offc Pro Italic",
                    "Arial Unicode MS Regular"
                ],
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            3,
                            25
                        ],
                        [
                            4,
                            30
                        ]
                    ]
                }
            },
            "metadata": {
                "mapbox:group": "1442411855944.8582"
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "Point"
                ],
                [
                    "==",
                    "labelrank",
                    1
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "marine_label_point_1",
            "paint": {
                "text-color": "#e4eaf6",
                "text-opacity": 0.25,
                "text-halo-color": "#405CB1",
                "text-halo-width": 1
            },
            "source-layer": "marine_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-max-width": 8,
                "visibility": "visible",
                "symbol-placement": "line",
                "text-field": "{name_en}",
                "text-line-height": 1.2,
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            3,
                            13
                        ],
                        [
                            5,
                            18
                        ]
                    ]
                },
                "text-font": [
                    "Kievit Offc Pro Italic",
                    "Arial Unicode MS Regular"
                ],
                "text-letter-spacing": 0.25
            },
            "metadata": {
                "mapbox:group": "1442411855944.8582"
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "LineString"
                ],
                [
                    "==",
                    "labelrank",
                    3
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "marine_label_line_3",
            "paint": {
                "text-color": "#e4eaf6",
                "text-opacity": 0.25,
                "text-halo-color": "#405CB1",
                "text-halo-width": 1
            },
            "source-layer": "marine_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-max-width": 15,
                "visibility": "visible",
                "symbol-placement": "line",
                "text-field": "{name_en}",
                "text-line-height": 1.2,
                "text-letter-spacing": 0.4,
                "text-font": [
                    "Kievit Offc Pro Italic",
                    "Arial Unicode MS Regular"
                ],
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            3,
                            15
                        ],
                        [
                            4,
                            20
                        ]
                    ]
                }
            },
            "metadata": {
                "mapbox:group": "1442411855944.8582"
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "LineString"
                ],
                [
                    "==",
                    "labelrank",
                    2
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "marine_label_line_2",
            "paint": {
                "text-color": "#e4eaf6",
                "text-opacity": 0.25,
                "text-halo-color": "#405CB1"
            },
            "source-layer": "marine_label"
        },
        {
            "interactive": true,
            "layout": {
                "text-line-height": 1.2,
                "text-size": {
                    "base": 1,
                    "stops": [
                        [
                            3,
                            25
                        ],
                        [
                            4,
                            30
                        ]
                    ]
                },
                "symbol-avoid-edges": false,
                "text-font": [
                    "Kievit Offc Pro Italic",
                    "Arial Unicode MS Regular"
                ],
                "symbol-placement": "line",
                "visibility": "visible",
                "text-field": "{name_en}",
                "text-letter-spacing": 0.4,
                "text-max-width": 4
            },
            "metadata": {
                "mapbox:group": "1442411855944.8582"
            },
            "filter": [
                "all",
                [
                    "==",
                    "$type",
                    "LineString"
                ],
                [
                    "==",
                    "labelrank",
                    1
                ]
            ],
            "type": "symbol",
            "source": "mapbox",
            "id": "marine_label_line_1",
            "paint": {
                "text-opacity": 0.25,
                "text-halo-width": 1,
                "text-halo-color": "#405CB1",
                "text-color": "#e4eaf6"
            },
            "source-layer": "marine_label"
        }
    ],
    "created": "2015-12-03T07:48:37.348Z",
    "id": "cihpxxwt8001jb0kpz9z559wm",
    "modified": "2015-12-03T07:48:37.348Z",
    "owner": "maper",
    "draft": false
}