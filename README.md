# LuaECS
纯Lua的简单ECS框架

#### 代码结构

- [Entity](lua/Entity.lua.txt)：实体，所有实体的基类
- [Component](lua/Component.lua.txt)：组件，仅包含状态，不包含行为，所有组件的基类
- [System](lua/System.lua.txt)：系统，仅包含行为，不包含状态，所有系统的基类
- [Collector](lua/Collector.lua.txt)：收集器，收集改动的Entity
- [Context](lua/Context.lua.txt)：上下文环境，可同时存在多个
- [Systems](lua/Systems.lua.txt)：管理所有系统，仅有一个

类似GameController或GameManager持有Context与Systems。