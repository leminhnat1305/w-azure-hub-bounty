genv().Configs = {
    ["Team"] = "Marines", -- Pirates/Marines
    ["Auto Ken"] = true,
    ["Auto Buso"] = true,
    ["Auto turn on race v3"] = true,
    ["Auto turn on race v4"] = true,
    ["FPS Boost"] = false,
    ["Click Time"] = 0.2,
    ["Bypass TP"] = true,
    ["Chat"] = {
        ["Enable"] = false,
        ["Message"] = {"made by Minh Nhat"}, -- Input your message here
    },
    ["Run When Low Health"] = {
        ["Enable"] = true,
        ["Health"] = 4000,
        ["Come back"] = false
    },
    ["Region"] = "Singapore", -- Singapore, United States, Germany, France, India, ??? ...
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.5,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.3,
                },
                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                }
            }
        },
        ["Fruit"] = {
            ["Enable"] = true,
            ["Delay"] = 0.5,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.5,
                },
                ["C"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 3,
                },
                ["V"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 3,
                },
                ["F"] = {
                    ["Enable"] = false,
                    ["HoldTime"] = 0,
                }
            }
        },
        ["Sword"] = {
            ["Enable"] = true,
            ["Delay"] = 1.25,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.15,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0.1,
                }
            }
        },
        ["Gun"] = {
            ["Enable"] = false
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                },
                ["X"] = {
                    ["Enable"] = true,
                    ["HoldTime"] = 0,
                }
            }
        }
    },
    ["Theme"] = {
        ["Enable"] = true,
        ["Name"] = "Hutao", -- Hutao, Raiden, Ayaka, Yelan
        ["Custom Theme"] = {
            ["Enable"] = true,
            ["Text Color"] = Color3.fromRGB(231, 85, 88),
            ["Character Position"] = UDim2.new(0.563000023, 0, -0.174999997, 0)
        }
    },
    ["Webhook"] = {
        ["Enable"] = true,
        ["Url"] = "https://discord.com/api/webhooks/1309904504778522706/UfwWJzd_IgJI_PnHsioroNwfBj6-5cYxJC44_20CGQtaDWHDLPjukh_YVbIIr1RKzlrV",
        ["Image"] = ""
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/verudous/Xero-Hub/main/autobounty.lua"))()
