# vehiclepack1
 Free Fivem vehicle pack with custom sounds and tuned


If you are using qbcore, to make your life easier... inside qb-core>shared>vehicle.lua...
QBShared.Vehicles = {
    --- Addon cars

    -- Aston Martin
    ['rmodmartin'] = {
        ['name'] = 'Rmod',
        ['brand'] = 'Aston Martin',
        ['model'] = 'rmodmartin',
        ['price'] = 450000,
        ['category'] = 'Aston Martin',
        ['hash'] = `rmodmartin`,
        ['shop'] = 'luxury',
    },

    -- Audi
    ['rmodrs6'] = {
        ['name'] = 'Rmod RS6',
        ['brand'] = 'Audi',
        ['model'] = 'rmodrs6',
        ['price'] = 70000,
        ['category'] = 'Audi',
        ['hash'] = `rmodrs6`,
        ['shop'] = 'luxury',
    },

    -- Bentley
    ['rmodbentley1'] = {
        ['name'] = 'Rmod 1',
        ['brand'] = 'Bentley',
        ['model'] = 'rmodbentley1',
        ['price'] = 450000,
        ['category'] = 'Bentley',
        ['hash'] = `rmodbentley1`,
        ['shop'] = 'luxury',
    },
    ['rmodbentleygt'] = {
        ['name'] = 'Rmod GTO',
        ['brand'] = 'Bentley',
        ['model'] = 'rmodbentleygt',
        ['price'] = 450000,
        ['category'] = 'Bentley',
        ['hash'] = `rmodbentleygt`,
        ['shop'] = 'luxury',
    },
    ['rmodbacalar'] = {
        ['name'] = 'Rmod Bacalar',
        ['brand'] = 'Bentley',
        ['model'] = 'rmodbacalar',
        ['price'] = 500000,
        ['category'] = 'Bentley',
        ['hash'] = `rmodbacalar`,
        ['shop'] = 'luxury',
    },

    -- BMW
    ['m4comp'] = {
        ['name'] = 'M4 Comp',
        ['brand'] = 'BMW',
        ['model'] = 'm4comp',
        ['price'] = 80000,
        ['category'] = 'Bmw',
        ['hash'] = `m4comp`,
        ['shop'] = { 'luxury' },
    },
    ['rmodbmwm8'] = {
        ['name'] = 'Rmod M8',
        ['brand'] = 'Bmw',
        ['model'] = 'rmodbmwm8',
        ['price'] = 120000,
        ['category'] = 'Bmw',
        ['hash'] = `rmodbmwm8`,
        ['shop'] = 'luxury',
    },
    ['rmodm8gte'] = {
        ['name'] = 'Rmod m8 gte',
        ['brand'] = 'Bmw',
        ['model'] = 'rmodm8gte',
        ['price'] = 120000,
        ['category'] = 'Bmw',
        ['hash'] = `rmodm8gte`,
        ['shop'] = 'luxury',
    },
    ['rm3e36'] = {
        ['name'] = 'e36',
        ['brand'] = 'Bmw',
        ['model'] = 'rm3e36',
        ['price'] = 110000,
        ['category'] = 'Bmw',
        ['hash'] = `rm3e36`,
        ['shop'] = 'luxury',
    },
    ['rmodm3e36'] = {
        ['name'] = 'M3 (Joker Edition)',
        ['brand'] = 'Bmw',
        ['model'] = 'rmodm3e36',
        ['price'] = 1200000,
        ['category'] = 'Bmw',
        ['hash'] = `rmodm3e36`,
        ['shop'] = 'luxury',
    },

    -- Bugatti
    ['rmodbugatti'] = {
        ['name'] = 'Rmod',
        ['brand'] = 'Bugatti',
        ['model'] = 'rmodbugatti',
        ['price'] = 1200000,
        ['category'] = 'Bugatti',
        ['hash'] = `rmodbugatti`,
        ['shop'] = 'luxury',
    },
    ['rmodchiron300'] = {
        ['name'] = 'Chiron 300',
        ['brand'] = 'Bugatti',
        ['model'] = 'rmodchiron300',
        ['price'] = 1255000,
        ['category'] = 'Bugatti',
        ['hash'] = `rmodchiron300`,
        ['shop'] = 'luxury',
    },

    -- Chevrolet
    ['rmodcamaro'] = {
        ['name'] = 'Camaro ZL1',
        ['brand'] = 'Chevrolet',
        ['model'] = 'rmodcamaro',
        ['price'] = 65000,
        ['category'] = 'Chevrolet',
        ['hash'] = `rmodcamaro`,
        ['shop'] = 'luxury',
    },

    -- Dodge
    ['rmodcharger69'] = {
        ['name'] = 'Charger 1969',
        ['brand'] = 'Dodge',
        ['model'] = 'rmodcharger69',
        ['price'] = 45000,
        ['category'] = 'Dodge',
        ['hash'] = `rmodcharger69`,
        ['shop'] = 'luxury',
    },
    ['dchallenger15'] = {
        ['name'] = 'Challenger 15',
        ['brand'] = 'dodge',
        ['model'] = 'dchallenger15',
        ['price'] = 60000,
        ['category'] = 'Dodge',
        ['hash'] = `dchallenger15`,
        ['shop'] = 'luxury',
    },
    ['CBRedeye'] = {
        ['name'] = 'Charger Hellcat SRT',
        ['brand'] = 'dodge',
        ['model'] = 'CBRedeye',
        ['price'] = 120000,
        ['category'] = 'Dodge',
        ['hash'] = `CBRedeye`,
        ['shop'] = 'luxury',
    },

    -- Farrari
    ['rmodf12tdf'] = {
        ['name'] = 'Rmod F12',
        ['brand'] = 'Ferrari',
        ['model'] = 'rmodf12tdf',
        ['price'] = 320000,
        ['category'] = 'Ferrari',
        ['hash'] = `rmodf12tdf`,
        ['shop'] = 'luxury',
    },
    ['rmodf40'] = {
        ['name'] = 'Rmod F40',
        ['brand'] = 'Ferrari',
        ['model'] = 'rmodf40',
        ['price'] = 450000,
        ['category'] = 'Ferrari',
        ['hash'] = `rmodf40`,
        ['shop'] = 'luxury',
    },

    -- lamborghini
    ['rmodsianr'] = {
        ['name'] = 'Rmod Sianr',
        ['brand'] = 'Lamborghini',
        ['model'] = 'rmodsianr',
        ['price'] = 220000,
        ['category'] = 'Lamborghini',
        ['hash'] = `rmodsianr`,
        ['shop'] = 'luxury',
    },

    -- Lexus
    ['lc500'] = {
        ['name'] = 'LC500', -- (Quinn Cruz)
        ['brand'] = 'Lexus',
        ['model'] = 'lc500',
        ['price'] = 75000,
        ['category'] = 'Lexus',
        ['hash'] = `lc500`,
        ['shop'] = 'luxury',
    },

    -- Mclaren
    ['rmodspeed'] = {
        ['name'] = 'Rmod Speed',
        ['brand'] = 'Mclaren',
        ['model'] = 'rmodspeed',
        ['price'] = 850000,
        ['category'] = 'Mclaren',
        ['hash'] = `rmodspeed`,
        ['shop'] = 'luxury',
    },

    -- Mercedes
    ['rmode63s'] = {
        ['name'] = 'Brabus e63',
        ['brand'] = 'Mercedes',
        ['model'] = 'rmode63s',
        ['price'] = 100000,
        ['category'] = 'Mercedes',
        ['hash'] = `rmode63s`,
        ['shop'] = 'luxury',
    },
    ['rmodc63amg'] = {
        ['name'] = 'C63',
        ['brand'] = 'Mercedes',
        ['model'] = 'rmodc63amg',
        ['price'] = 70000,
        ['category'] = 'Mercedes',
        ['hash'] = `rmodc63amg`,
        ['shop'] = 'luxury',
    },
    ['rmodgt63'] = {
        ['name'] = 'Brabus Taxi',
        ['brand'] = 'Mercedes',
        ['model'] = 'rmodgt63',
        ['price'] = 36000,
        ['category'] = 'Mercedes',
        ['hash'] = `rmodgt63`,
        ['shop'] = 'luxury',
    },

    -- Nissan
    ['rmodgtr50'] = {
        ['name'] = 'Rmod Gtr50',
        ['brand'] = 'Nissan',
        ['model'] = 'rmodgtr50',
        ['price'] = 45000,
        ['category'] = 'Nissan',
        ['hash'] = `rmodgtr50`,
        ['shop'] = 'luxury',
    },
    ['rmodskyline34'] = {
        ['name'] = 'Rmod Skyline34',
        ['brand'] = 'Nissan',
        ['model'] = 'rmodskyline34',
        ['price'] = 45000,
        ['category'] = 'Nissan',
        ['hash'] = `rmodskyline34`,
        ['shop'] = 'luxury',
    },
    ['agtr35'] = {
        ['name'] = 'Gtr (Pokemon Edition)',
        ['brand'] = 'Nissan',
        ['model'] = 'agtr35',
        ['price'] = 1200000,
        ['category'] = 'Nissan',
        ['hash'] = `agtr35`,
        ['shop'] = 'luxury',
    },
    ['rmgtr35'] = {
        ['name'] = 'Gtr (Rick & Morty Edition) ',
        ['brand'] = 'Nissan',
        ['model'] = 'rmgtr35',
        ['price'] = 1200000,
        ['category'] = 'Nissan',
        ['hash'] = `rmgtr35`,
        ['shop'] = 'luxury',
    },

    -- Porsche
    ['718caymans'] = {
        ['name'] = '718',
        ['brand'] = 'Porsche',
        ['model'] = '718caymans',
        ['price'] = 160000,
        ['category'] = 'Porsche',
        ['hash'] = `718caymans`,
        ['shop'] = {'luxury'},
    },
    ['cgt'] = {
        ['name'] = 'cgt',
        ['brand'] = 'Porsche',
        ['model'] = 'cgt',
        ['price'] = 255000,
        ['category'] = 'Porsche',
        ['hash'] = `cgt`,
        ['shop'] = {'luxury'},
    },
    ['maj935'] = {
        ['name'] = '935',
        ['brand'] = 'Porsche',
        ['model'] = 'maj935',
        ['price'] = 120000,
        ['category'] = 'Porsche',
        ['hash'] = `maj935`,
        ['shop'] = {'luxury'},
    },
    ['pcs18'] = {
        ['name'] = 'Cayenne S 2018',
        ['brand'] = 'Porsche',
        ['model'] = 'pcs18',
        ['price'] = 120000,
        ['category'] = 'Porsche',
        ['hash'] = `pcs18`,
        ['shop'] = {'luxury'},
    },
    ['p911'] = {
        ['name'] = '911 Vintage',
        ['brand'] = 'Porsche',
        ['model'] = 'p911',
        ['price'] = 150000,
        ['category'] = 'Porsche',
        ['hash'] = `p911`,
        ['shop'] = {'luxury'},
    },

    -- Volkswagen
    ['rmodmk7'] = {
        ['name'] = 'Rmod Golf',
        ['brand'] = 'Volkswagon',
        ['model'] = 'rmodmk7',
        ['price'] = 25000,
        ['category'] = 'Volkswagen',
        ['hash'] = `rmodmk7`,
        ['shop'] = 'luxury',
    },