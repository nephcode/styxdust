![Cover](https://github.com/nephcode/styxdust/blob/main/.github/images/githubReadmeHeader.png)

# STYXDUST
RELEASE LIB TO VITE REACT 19 RR7 UPGRADE WITH TEST


## INFORMATIONS

| WHERE   | URL                                         |
| :------ | ------------------------------------------- |
| DISCORD | [#](#)                                      |
| WWW     | [Styxdust](https://styxdust.youcodeuse.com) |

| WHO IS   | FOR             |   COMPANY    | CONTACT | DISCORD |
| :------- | --------------- | :----------: | ------- | :-----: |
| Nephelim | Head of concept | illuminateam | #       |   YES   |

## TECHNO

| TECHNO   | SPEC                       |
| :------- | -------------------------- |
| FRONTEND | `SASS` `STYLED COMPONENTS` |
| BACKEND  | `REMIX`                    |
| BUNDLE   | `VITE` >> `CREATE APP`     |

## DOCUMENTATION

`styxdust` is a React & Remix SSR component that provides a customizable modal dialog. It allows you to display content in a modal window and includes a close button to hide the modal.

## USAGE

To use the `CustomModal` component, import it into your React project and include it in your JSX. You can control the visibility of the modal by passing the `isDisplayed` prop, and handle the close action with the `onCloseModal` prop.

### EXAMPLE

```jsx
import React, { useState } from 'react'
import CustomModal from './CustomModal'

const App = () => {
  const [isModalOpen, setIsModalOpen] = useState(false)

  const handleOpenModal = () => {
    setIsModalOpen(true)
  }

  const handleCloseModal = () => {
    setIsModalOpen(false)
  }

  return (
    <div>
      <button onClick={handleOpenModal}>Open Modal</button>
      <CustomModal
        isDisplayed={isModalOpen}
        onCloseModal={handleCloseModal}
        content={<div>Your modal content here</div>}
      />
    </div>
  )
}

export default App
```

## PROPS

- `isDisplayed` (boolean): Controls whether the modal is visible or not. Default is `false`.
- `onCloseModal` (function): Function to call when the close button is clicked.
- `content` (node): The content to display inside the modal.

## STYLING

The modal can be styled using CSS. The following classes are available:

- `custom-modal`: The main container for the modal.
- `custom-modal-main`: The inner container for the modal content.
- `custom-modal-btn-close`: The close button.
- `custom-modal-content`: The container for the modal content.

You can customize these classes in your CSS file to match your application's design.

// Exportation du composant pour pouvoir l'utiliser dans d'autres fichiers
export default CustomModal;

![Cover](https://github.com/nephcode/underconstruction-react/blob/main/.github/images/githubReadmeFooter.png)
