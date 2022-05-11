# Redux presentation

## Goal
Workshop presentations, code as you speak. Make them inspired with awe.


## Scope
1) **Redux Store box** (most simple redux model (subscribe, dispatch))
2) **Reducer** as function (ternary, if, switch)
3) **Action** as object and Action creator
4) **UI** simple rendering function (adder, list -> AJAX list)
5) **Rules of redux** reducers as **pure** functions, immutability, non-async nature 
6) **Combine reducer** manually -> show purpose
7) **Middleware** async actions
8) **Unsubscribe** for Gods sake!

## Scenario
1)  **Intro**, make short introduction by presenting simplest redux-system model (state object, dispatch, subscribe) and data flow using follow-up visuals. **[2m]**
2) **Increment reducer + store creation**, Begin with blank file. We live-code simplest reducer + 1 action (-> action creator). Presentation in browser console.  **[3m]**
3)  **Add UI**, Create simple UI (counter and + button) to support state presentation and action dispatch. UI should mimic React component, so we render UI programmatically. **[5m]**
4)  **More actions**, enable +,- and 0 actions, extend reducer ( ?:, if, {[key]}} ) and UI **[5m]**
5) **More reducers + Following UI**, reducer -> {list of strings}, UI -> {input and list presentation} (replace previous reducer temporary) **[7m]** 
6) **Working together** combine reducers manually -> use combineReducers **[5m]**
7) **Three principals** present (3 principals of redux)[https://redux.js.org/understanding/thinking-in-redux/three-principles]
8) **Middleware** TBD

** Resources
* Visuals
    1) Simplified Redux model (dispatch, subscribe box)
    2) [Redux-data-flow-paint](https://www.autodraw.com/share/SE4I2LPS2LME) 
    2) [Redux one-way dataflow](https://d33wubrfki0l68.cloudfront.net/73bb62ebc338fcd64ee95bde18684ffe3b3bb379/dac4f/assets/images/one-way-data-flow-04fe46332c1ccb3497ecb04b94e55b97.png)
    3) [Redux async dataflow](https://redux.js.org/assets/images/ReduxAsyncDataFlowDiagram-d97ff38a0f4da0f327163170ccc13e80.gif)

## Terms
* state
* action
* reducer
* pure function
* immutability
* middleware
* thunk
* selector
* memorized selector

(...arg) => res

res -> (F, arg)