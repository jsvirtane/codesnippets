import { useReducer } from 'react'

const useToggle = () => {
    const [isOpen, toggleIsOpen] = useReducer((state) => {
        return !state
    }, false)

    return {
        isOpen,
        toggleIsOpen
    }
} 
export default useToggle
